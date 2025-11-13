---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My name is Luca Morando and I am an Italian researcher working in the US. 

Currently, I am a postdoctoral associate at New York University and a Visiting Postdoctoral Scholar at U.C. Berkeley, in particular in the [Agile Robotics and Perception Lab](https://arplaboratory.github.io/)(ARPL), headed by Prof. Giuseppe Loianno. 
At ARPL, I work on aerial robotics autonomy, especially for long range application for fixed wing aircrafts and Human Robot Interaction using Mixed Reality techinques. 

I joined ARPL as a Visiting Ph.D. student in November 2021 where I spent two years before getting my International Ph.D. in Robotics and Autonomous System from the [University of Genoa](https://unige.it/en), under the supervision of both Prof. Loianno and Prof. Antonio Sgorbissa. 
Prior to the Ph.D., I obtained my Master Degree from University of Genoa in Robotics Engineering, where I spent a year in an International Exchange Program at the [Universitè de Technologie de Compiegne (UTC)](https://www.utc.fr/),  where I conducted my Master Thesis project at the [Heudyasic Lab](https://www.hds.utc.fr/en/) under the supervision of Prof. Pedro Garcia. 
I got my bachelor degree as well from University of Genoa in Biomedical Engineering, where I participated to 6 months Interniship at the Italian Institude of Technology. 

My research has been validated through DARPA and Army Research Lab field trials, published in leading IEEE venues, and resulted in multiple journal articles and U.S. patents.


## Ph.D. And Postdoc Research 

Autonomous drones, both wing based and quadrotors, are becoming indispensable in critical missions such as search and rescue and disaster response. Differently from other robotics systems, autonomous drones have the capability to fly, cover long distances and also explored constrained outdoor and indoor environments where other robotics agent would easily fail. Despite this, today's system still lacks fully autonomy capability and they ofter requires expert human pilot intervention. Additionally, despite already used as important tool in emergency scenarios and military applications, still lacks proper mechanism for an intelligent interaction with non expert humans, that can enhance them from simple tools, to real human collaborator and companion in various missions. 
During my research, I fully focused on building autonomous stack based on a simple premise:

*Enabling safe and agile autonomy in unknown environments by adapting to shifting condition, enabling long range and energy harvesting capabilities and provide an enhanced level of collaboaration with humans in complex mission sceanrios.*

### Autonomous and Agile Planning and Control for Fixed Wing Aerial Vehicle
(put video plane flyig during the glide at coney island and image google earth of the paper)
Despite their great potential across domains such as environmental monitoring, disaster response, agriculture, and logistic, unmanned Fixed Wing UAVs, which stand out for their long range endurance, and high cruise speed compared to multirotor aerial vehicles, present a very complex coupled and highly non-linear dynamics, which is strictly affected by aerodynamics effects acting on the airframes at different flying regimes. These characteristics, enhanced by the external wind disturbances, can pose severe problems on planning and control of flight trajectories. In this direction, my research has been focused in designing flying architecture that leverages the complex dynamics of the aircraft, and simplifying them for control objectives leveraging the mathematical formulation provided by the Differential Flatness for geometric control. 
To further keep the plane always in a safe flying envelope, continuous flying trajectories are optimized based on Bernestin Polynomials, with the characteristic of being dynamic aware, wind aware for optimal crusing and able to generate optimal gliding conditions for Energy Harvesting. 
Additionally, we developed a fully dynamic and aerodynamic aware NMPC for optimal tracking of the genrated trajectories and disturbances rejection. 
This framework, tested on various platforms, provides resilient flight autonomy for long range fixed wing applications. 

### Human Robot-Drone Interaction for shared collaboration and exploration of indoor constrained environments through Mixed Reality
During my research I have always been aware that Aerial Robots have the potential to play a crucial role in assisting humans in complex and dangerous
tasks without requiring an expert human pilot that always control them through teleoperation devices based on simple joystics. The goal of my research has been motivated by creating autonomy and interaction solutions to decrease users’ cognitive and physical workload while working with a aerial robotic agent, makig the interaction so natural that the human does not consider them as machines but as real collaborators, that they can trust, and can guide them in dangerous and complicated exploration. In this direction, I develop a bidirectional spatial awareness stack based on a virtual-physical interaction leveraging Mixed Reality interaction tools with the goal to create a virtual immersive environment integrated in the real word where the users and the robots can sinuosly interact and sharing spatial and perception information and control commands minimizimng the user mental loading. 
To achieve this, the user can control the robot giving him spatial waypoints or directly drag the virtual representation in a virtually created environment, visible in Mixed Reality, dynamically enhanced with the robot mapping capabilities. 
Additionally, the user can be guided by the robot as well, which it runs an onboard autonomous pipeline based on generation of obstacles, user and dynamic aware flying trajectories, which acts as a safety guaranteed for the robot navigation, and provides a force feedback to the user if he tries to pull the robot away from it. 
User case studies shows how the bi-directional planner helped spatial awareness based on MR increase the user interaction efficiency thus reducing the workload. Additionally the MR has been developed as a web based framework, cross platform and accessible from anywhere by anyone. 

### Efficient Navigation and Inspection of LArge Photovoltaic Solar Plants using autonomous quadrotors


In addition, many applications
will require aerial robots to be ubiquitous and share the same environment with human operators.
Therefore, this calls for novel solutions to enable seamless, transparent, and efficient human-drone
collaboration and co-working in the same workspace. In this paper, we present a tele-immersive
approach that fosters cognitive and physical collaboration between humans and robots through
Mixed Reality. We develop a bidirectional spatial awareness module and a virtual-physical interaction
framework integrated into a head-mounted MR display



Yet today’s systems still require expert human pilots and they are lacking of proper mechanism of interaction with non-expert human  because autonomy fails where it matters most: in complex, GPS-denied, and rapidly changing environments. GPS signals vanish, maps become outdated, and controllers tuned in the lab collapse when conditions shift. During my Ph.D., I rebuilt the autonomy stack around a simple premise:

Enabling safe and agile autonomy in unknown environments by adapting to shifting conditions, reacting instantly to obstacles, and relying only on what the robot can directly observe.


Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
