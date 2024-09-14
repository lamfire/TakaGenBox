### TakaGenBox仅学习使用，请勿作非法用途
forked from takagen99/Box (Updated: 06bfe75bffefbef060785408d5712a960779ec79)


#### Credits
This repo relies on the following third-party projects:
```
CatVodTVOfficial/TVBoxOSC
q215613905/TVBoxOS (Updated: a545c27b99b6d6d9e54196b8a0adcf3b56a97ddf)
takagen99/Box (Updated: 06bfe75bffefbef060785408d5712a960779ec79)
```

=== Source Code - Editing the app default settings ===
/src/main/java/com/github/tvbox/osc/base/App.java
```
    private void initParams() { 

        putDefault(HawkConfig.HOME_REC, 2);       // Home Rec 0=豆瓣, 1=推荐, 2=历史
        putDefault(HawkConfig.PLAY_TYPE, 1);      // Player   0=系统, 1=IJK, 2=Exo
        putDefault(HawkConfig.IJK_CODEC, "硬解码");// IJK Render 软解码, 硬解码
        putDefault(HawkConfig.HOME_SHOW_SOURCE, true);  // true=Show, false=Not show
        putDefault(HawkConfig.HOME_NUM, 2);       // History Number
        putDefault(HawkConfig.DOH_URL, 2);        // DNS
        putDefault(HawkConfig.SEARCH_VIEW, 2);    // Text or Picture

    }
```