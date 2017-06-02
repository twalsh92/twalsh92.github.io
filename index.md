# Welcome

I'm a PhD student at the [University of Sheffield](http://shef.ac.uk), a member of the [Testing Research Group](https://www.sheffield.ac.uk/dcs/research/groups/testing/home), researching novel methods for quality assurance of responsive web pages.

## About Me

### Education

I graduated with a First Class Bachelor's degree in Software Engineering from the University of Sheffield in 2014, during which I developed advanced skills in software development, testing, project and team management. Before that, I studied at Winstanley College where I obtained A-grade A levels in Computing, Mathematics, Further Mathematics and Physics.

### Employment

#### Graduate Teaching Assistant, University of Sheffield - September 2014 - Present
Responsible for assisting undergraduate students during weekly lab classes, helping solve technical issues and answering any questions they may have. I have also had the opportunity to lead certain lab classes and to work alongside lecturers in the planning of future lab classes.

#### Software Testing and Development Intern, SkillFlick - July 2013 - September 2013
Worked primarily as a Ruby on Rails software tester, developing a fully automated acceptance test suite for the application using popular technologies such as Cucumber. Also undertook some regular Ruby on Rails development work for a smaller companion tool for the site which handled the booking of photoshoots for users of the site.

### Interests

Outside of the laboratory, I'm a big fitness fan and like to run or get out on my bike whenever I can. When it comes to relaxing, I am an avid fan of literature and music, and I'm in the process of building up extensive book and vinyl record collections.

## Publications

### Automated Layout Failure Detection for Responsive Web Pages without an Explicit Oracle - Thomas A. Walsh, Gregory M. Kapfhammer and Phil McMinn
#### International Symposium on Software Testing and Analysis (ISSTA 2017)

As the number and variety of devices being used to access the World Wide Web grows exponentially, ensuring the correct presentation of a web page, regardless of the device used to browse it, is an important and challenging task. When developers adopt responsive web design (RWD) techniques, web pages modify their appearance to accommodate a device’s display constraints. However, a current lack of automated support means that presentation failures may go undetected in a page’s layout when rendered for different viewport sizes. A central problem is the difficulty in providing an automated "oracle" to validate RWD layouts against, meaning checking for failures is largely a manual process in practice, which results in layout failures in many live responsive web sites. This paper presents an automated failure detection technique that checks the consistency of a responsive page’s layout across a range of viewport widths, obviating the need for an explicit oracle. In an empirical study, this method found failures in 16 of 26 real-world production pages studied, detecting 33 distinct failures in total.

### ReDeCheck: An Automatic Layout Failure Checking Tool for Responsively Designed Web Pages - Thomas A. Walsh, Gregory M. Kapfhammer and Phil McMinn
#### "Demonstrations" track, International Symposium on Software Testing and Analysis (ISSTA 2017)

Since people frequently access websites with a wide variety of devices (e.g., mobile phones, laptops, and desktops), developers need frameworks and tools for creating layouts that are useful at many viewport widths. While responsive web design (RWD) principles and frameworks facilitate the development of such sites, there is a lack of tools supporting the detection of failures in their layout. Since the quality assurance process for responsively designed websites is often manual, time-consuming, and error-prone, this paper presents ReDeCheck, an automated layout checking tool that alerts developers to both potential unintended regressions in responsive layout and common types of layout failure. In addition to summarizing ReDeCheck’s benefits, this paper explores two different usage scenarios for this tool that is publicly available on GitHub.

### Automatic Detection of Potential Layout Faults Following Changes to Responsive Web Pages - Thomas A. Walsh, Phil McMinn and Gregory M. Kapfhammer
#### INTERNATIONAL CONFERENCE ON AUTOMATED SOFTWARE ENGINEERING (ASE 2015)

[Download PDF](ase2015.pdf)

Due to the exponential increase in the number of mobile devices being used to access the World Wide Web, it is crucial that web sites are functional and user-friendly across a wide range of web-enabled devices. This necessity has resulted in the introduction of responsive web design (RWD), which uses complex cascading style sheets (CSS) to fluidly modify a web site’s appearance depending on the viewport width of the device in use. Although existing tools may support the testing of responsive web sites, they are time consuming and error-prone to use because they require manual screenshot inspection at specified viewport widths. Addressing these concerns, this paper presents a method that can automatically detect potential layout faults in responsively designed web sites. To experimentally evaluate this approach, we implemented it as a tool, called REDECHECK, and applied it to 5 real-world web sites that vary in both their approach to responsive design and their complexity. The experiments reveal that REDECHECK finds 91% of the inserted layout faults.
