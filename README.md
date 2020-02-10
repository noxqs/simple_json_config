# simple_json_config
This is a plain simple (less than 60 lines) jet powerful json config class, easy to use in your project where you can store all your app settings.

**Examples**:
```cfg = Simple_json_config(autoSave=True, configFile="myConfig.json", default={'items':{}, 'rois':{}})
cfg.noot="noot"
cfg['aap']="mies"
print ("res1:",cfg.noot)
print ("res2:",cfg['aap'])
print ("res3:",cfg.aap)```

autoSave will save after every change. 
configFile is the name of your config. It will be stored in the same folder as your main python script.
the variable default holds all the info that will be written if either the file does not exist or the json is invalid.

Hope you like it, easy enough to implement in your project.
