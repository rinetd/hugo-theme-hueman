# hugo-theme-hueman

Demo: [http://blog.pytool.com/](http://blog.pytool.com/)

## Step1 Install Hugo


## Step2 Create your site

```  
hugo new site your-blog-name  
cd your-blog-name  
```  

## Step3 Clone the theme repo  

```  
git clone https://github.com/rinetd/hueman.git themes/hueman  

# replace config file  
rm config.toml  
cp themes/hueman/config.yaml .  
```  

## Step4 Start your site  

```  
# new content  
hugo new about.md  
# start server  
hugo server  
```  

## Step5 Have Fun  

Now you can open [http://localhost:1313](http://localhost:1313)  

Modify the config.yaml and other things, and have fun!  

You can also make this repo as submodule:  

```  
git init  
```  
