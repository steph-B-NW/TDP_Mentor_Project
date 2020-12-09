# In Review: Second attempt

## The goals on reflection

I decided that my first task would be to review with my colleagues and understand what I was missing regarding my approach. I was able to develop a more targeted approach this time, and plan a lot more efficiently. I knew I would have to essentially break down and rebuild my structure to accomodate each stage individually, and re-order my jenkinsfile to suit the pipeline. In my previous attempt, I was focussed on building and testing each stage in the pipeline individually in order to tackle each problem as it was presented. This presented a majour issue as soon as my Jenkinsfile began to have trouble building, and ate up a lot of my time just attempting to resolve a simple syntax issue. This time, I would build as many scripts as I could before attempting an initial build, and make bugfixes the latter stage, as the priority was building the foundation and building from there.

## Building structure and code

I tore down much of my initial structure, and took a lot of advice regarding the pipeline. This time, I would use the pipeline as a timeline for executing code using small bash scripts to execute larger playbooks and scripts down the timeline. This allowed me to tackle each section as dependencies and build orders. 
