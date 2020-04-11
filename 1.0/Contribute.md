# Contribute

---

## Mission

This repository is meant to help all those seeking knowledge regarding all things Final Fantasy XIV. 

It's very important that all information contributed to this repository is correct and not based on speculation. While speculation is definitely allowed, please make sure to signify any speculative information so the reader may make better decisions based on the information provided.

## How To Contribute

This documentation is all managed through a public GitHub repository. All are welcome to submit contributions via the git methods.

### Suggested Method

Software: Typora

- Website: [Typora.io](https://typora.io/)
- Download: [Windows, Mac, & Linux](https://typora.io/#download)

#### Typora

Typora comes with a method of uploading images built in. It's default is PicGo sm.ms. You'll need to create an account there and obtain an API key.

API Token: [https://sm.ms/home/apitoken](https://sm.ms/home/apitoken)

##### Configuration

Go to File > Preferences > Image 

Click the Download button, it should install. After that's complete, click the "Open Config File" button. See below for an example configuration.

![](https://i.loli.net/2020/04/11/LcaS8kjhPgJuyGo.png)

*Example Configuration*

```json
{
  "picBed": {
    "uploader": "smms", 
    "smms": {
      "token": "YourAPITokenHere" 
    }
  },
  "picgoPlugins": {} 
}
```

