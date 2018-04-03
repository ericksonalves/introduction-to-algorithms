## Comments

Repository organization:
- Add _.DS_Store_ to __.gitignore__
- Improve __README.md__
- Include __BUILDING.md__
- Since the repository name is _weaver-report_, change folder names to _scripts_ (_weaver-scripts_) and _template_ (_weaver-template_)

Code organization:
- __weaver-template__
    - Refer to general tips
- __class_bug.py__
    - I think you can rewrite this class to make it more generic and then specialize it to the way you need right now
- __main.py__
    - Hello
    - World
- __sprint_bugs.txt__ and __sprint_metrics.txt__
    - Since it is an empty file, why keeping it?
- __weaver-report-config.yml__
    - This is probably configured before running it, right?! This information should be available in __BUILDING.md__
- __weaver_report.sh__
    - Magic numbers everywhere (refer to this [link](https://en.wikipedia.org/wiki/Magic_number_(programming)#Unnamed_numerical_constants))
    - Do not mix languages. Since you want to share your code with the community, it should entirely be in English.
    - How about breaking down this file in small chunks by functionality?

General tips:
- Have some look at this [link](https://en.wikipedia.org/wiki/Anti-pattern#Programming)
- Format your code properly (refer to this [link](https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118))
