# ez_juce_plugin_template
this is the project that I use as the template for my juce audio plugins. 
It has a neat build script that automatically generates releases

## how to use this template
1. got to https://github.com/original-picture/ez_juce_plugin_template and click the green "Use this template" button in the top right corner
2. once your new respository has been created, go into the settings page for the respository, then click actions, click general, scroll down to workflow permissions, and select "Read and write permissions".
   If you don't do this, automatic release generation will fail  

> [!IMPORTANT]
> this repo's github actions workflow assumes that the name of the cmake target for you plugin is exactly the same as the name of your github repo  
> the CI will break if they don't match!
