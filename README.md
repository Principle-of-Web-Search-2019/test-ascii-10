作业内容:
============================

myHomeWork1:
---------------------
>>第一个新闻标题过滤程序，实现关键词逻辑表达式的解析，例如 苹果 and (芯片 or 高通)，即为查找含苹果，而且含芯片和高通之一的新闻标题。将得到的标题显示，关键词标红或者标蓝。\
>>实现方式是遍历一遍关键词逻辑表达式，找到所有关键词（不包含and，or，not），然后替换关键词逻辑表达式为形如 '苹果' in title and ('芯片' in title or '高通' in title)。\
>>之后遍历所有的title，然后eval上面的表达式，即可判断该标题是否符合逻辑表达式的要求。\
>>如果符合逻辑表达式的要求，则将关键词替换为HTML语句并调用display输出即可。\
