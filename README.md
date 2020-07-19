# my-browser-bookmark

### Introduction

**Sync my own bookmarks between different browsers by [书签同步](https://chrome.google.com/webstore/detail/%E4%B9%A6%E7%AD%BE%E5%90%8C%E6%AD%A5/fbcbemgibdnpboehnfcnkegefaomnlbk?hl=zh) plugin
(Chrome | Edge | Firefox are supported)**

### Usage

1. Search `书签同步` plugin in your browser's webstore and add it to extensions.

2. Make sure you already have a Github account. If not, you are supposed to register one.

3. Create a new repository named by yourself, for example, `chrome-bookmark` is accepted. You can make it `public` or `private` by yourself.

4. Create an empty `.json` file named by yourself, for instance, `bookmarks.json`.

5. Get into `Settings/Developer settings/Personal access tokens` (not this repository's setting, it's your account settings).

6. Generate new token, note by yourself, for example, `Browser-Bookmarks`.

7. Select scopes, give permissions at least these two: `write:packages` and `read:packages`.

8. Copy you token. Make sure you store it carefully because you cannot see it when access this site again.

9. Plugin configuration: input your Github username, token, and path like `your-repository-name/your-file-name.json`. For instance, `my-browser-bookmark/bookmarks.json`
    
10. Choose `Remember me` and click `Upload` button. When you want to sync bookmarks in other browsers, make sure the information you input are same and clikc `Download` button,
then bookmarks are synchronized successfully.
