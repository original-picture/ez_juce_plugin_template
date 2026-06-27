# ez_juce_plugin_template
this is the project that I use as the template for my juce audio plugins. 
It has a neat build script that automatically generates releases

## how to use this template
```bash
gh repo create --template "https://github.com/original-picture/ez_juce_plugin_template" --clone
```  
// FIXME: submodules don't get initialized...

> [!IMPORTANT]
> this repo's github actions workflow assumes that the name of the cmake target for you plugin is exactly the same as the name of your github repo  
> the CI will break if they don't match!
