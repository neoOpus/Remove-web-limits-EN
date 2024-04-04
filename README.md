# Remove-web-limits- Web page unrestricted
Online Installation [Greasy Fork](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified)

You can unblock copy, cut, select text, right-click menu, and kill most websites.

After installation a small translucent box will appear in the top right corner of the page, although the script has some websites built in, if the website you are viewing does not work, you can slide your mouse over this and click the checkbox to make it work for that website. If it does not work you can give feedback here

The original author [cat73](https://cat7373.github.io/remove-web-limits/) , has stopped maintaining it, and its related links [Greasy Fork](https://greasyfork.org/zh-CN/scripts/14146) , [GitHub](https://github.com/Cat7373/remove-web-limits) , have been changed because of [conflict](https://greasyfork.org/zh-CN/forum/discussion/21298/x?locale=zh-CN#) with [search jump script](https://greasyfork.org/zh-CN/scripts/27752-searchenginejump) .

Since the original author has stopped maintaining it due to work, be sure to give feedback under my [GitHub](https://github.com/qxinGitHub/Remove-web-limits-/issues) or [Greasy Fork](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified) with the relevant URL if you are giving feedback. If it's a thank you go to [original author's GitHub](https://github.com/Cat7373/remove-web-limits) to thank him.  

## Related notes
0. Some pages the original author's script works and mine doesn't, so try the original author's when that happens.
1. Text on flash pages cannot be copied
2. The text on the link can be copied by holding down the alt key to select
3. If used for video sites, it will make the video drag bar unusable. Please turn off the use of rules for video sites after copying is complete.
4. Some sites will still prompt you to open a vip or pay for it, but try pasting it, some will work

<!-- 
## Some website records
### Unavailable websites
- http://www.wodocx.com/ documentation site, using images to display img
### Hint, but it's copied successfully
- http://www.jianbiaoku.com/ Build a library of bids: Copy prompted for VIP, but it was copied successfully
- www.51dongshi.com prompts for a paid copy, but the copy was successful

### Other unresolved
- https://www.dydata.io/datastore/detail/1996453535188914176/ won't load, keeps spinning in circles
- https://www.lovehtbooks.com/ After registering an account, the login prompted an account or password error
 -->

## Update history
 > v4.4.8 2022-12-13
  - Added: Some websites have been added to the default rules ("www.daodoc.com", "www.wcqjyw.com", "www.szxx.com.cn")
 > v4.4.7 2022-11-24
  - Added: Added some sites
  - Exclude: Exclude some websites, solve Zhihu login problem
 > v4.4.6 2021-06-09
  - Added: www.bimiacg.net
 > v4.4.5 2021-03-19
  - Added: www.uta-net.com
 > v4.4.4 2021-03-13
  - Add: xiegw.cn
 > v4.4.3 2021-03-13
  - Added: partial support for chuangshi.qq.com
 > v4.4.2 2021-03-10
  - add myhtebooks.com
 > v4.4.1 2021-03-07
  - Added: votetw.com
  - Added: boke112.com
  > v4.4.0 2020-08-03
  - Increase the copy shortcut key by default Cttl + C, which can be changed to F1 or closed (even if the website is not in the blacklist, it will work)
  - The setting interface, the problem that the close button cannot be used
  - Exclude Bilibili/youtube video playback interface
  - The problem that the hidden button cannot take effect
  - Added several sites
  > v4.3.3 2020-02-23
  - Add clear settings button
  - Added www.uslsoftware.com website
  > v4.3.3 2020-02-23
  -Fixed a problem that may lead to not being able to hide
  > v4.3.2 2020-02-21
  - Incorrect internal parameters cause new users to be unable to use normally. Version 4.3.0 causes
  > v4.3.1 2020-02-20
  - Style fine-tuning
  > v4.3.0 2020-02-19
  - Change settings menu, button can be hidden
  > v4.2.0 2020-02-16
  - Previous release dates can be found at [Greasy Fork](https://greasyfork.org/zh-CN/scripts/28497-remove-web-limits-modified).
  - Get all nodes including nodes in iframe
  - Corrected [Begonia Cultural Novel Website](https://www.myhtlmebook.com/)
  > v4.1.4 2018-07-02
  - remove ads
  > v4.1.3 2018-06-30
  - After the Baidu page is turned, it will occupy the content of the webpage, thanks for the feedback from Gem Tre in the comment area
  > v4.1.2 2018-06-29
  - Updated ads
  > v4.1.1 2018-06-26
  - Added settings menu
  - Added ads
  > v4.0.0 2018-06-11
  - Version 4.0.0, tidied up the code
  > v3.2.3 2018-06-05
  - Thanks to the help of JsonBorn in the comment area. Currently, for station b, only the video area and the drama area are excluded
  > v3.2.2 2018-05-18
  - Unable to copy the dynamic problem of station b, thanks for the feedback from peter17ji in the feedback area
  > v3.2.1 2018-05-10
  - Commenting out the problem that the script will not take effect, thanks to Fengyifu in the comment area for feedback
  - Change the size of the window, if the button leaves the visible window, it will automatically move to the bottom
  > v3.2.0 2018-04-18
  - Increase the adsorption edge, you can drag the position, because of laziness, currently it can only be adsorbed on the left
  > v3.1.0 2018-04-02
  - Some websites will obtain wrong node objects, resulting in abnormal termination of the program. Thanks for the feedback from Deleted user 163399 in the comment area
  > v3.0.7 2018-03-13
  - Zhihu cannot reproduce the problem, thanks to the feedback from user Qun Wang
  > v3.0.6 2018-03-09
  - Changed English and Japanese names to distinguish it from the original script
  > v3.0.5 2018-02-15
  - Add beforeunload, remove the leave restriction, thanks for the lickety suggestion in the comment area,
  > v3.0.4 2018-02-15
  - The script excludes Station B, Panda Live Website by default,
  > v3.0.3 2018-02-15
  - Websites such as App Store are transparent after selection, giving users the illusion that they cannot be selected,
  - At the same time, correct the situation that the page of Longteng.com (www.ltaaa.com) turns blue
  > v3.0.2 2018-01-11
  - Some website pages turn blue, thanks to Liang_Jinpeng's feedback in the comment area
  > v3.0.1 2018-01-02
  - After checking, the page will no longer be actively refreshed;
  - After the text is selected, the color will be changed to white on a blue background. After the text is selected on some pages, the background and font color will not change, giving people a feeling that they cannot be selected
  > v3.0.0 2017-11-28
  - Starting from this version, the list will be uploaded to my server to integrate the blacklist,
  > v2.4.11 2017-11-21
   - Zhihu can’t click the drop-down association search in the search box, thanks to w153140 user feedback
  > v2.4.10 2017-11-20
   - Saving data before may result in saving an empty string, causing all complete matches to succeed
  > v2.4.9 2017-10-17
  - Increase the clearing of mousemove events, thanks to weijen6 user feedback
  > v2.4.8.1 2017-10-12
  - Streamline useless code
  > v2.4.7 2017-10-11
  - Crashes, don't know the cause of the problem, or even from which version the problem arises. Roll back to 2.4.3. Make changes on this version.
  - gm_getvalue does not work intermittently on site city.udn.com.
  - Array.from cannot convert the set structure to an array, and the return value is undefined. Thanks for the feedback from weijen6 in the comment area
  > v2.4.6 2017-09-28
  - ~~You can easily view the list of blocked websites~~
  > v2.4.5 2017-08-31
  - ~~Setting menu position offset phenomenon~~
  > v2.4.4 2017-08-27
  - ~~ Added "http://bbs.coocaa.com, http://luxmuscles.com" to the blacklist, thanks to zhangbaida and another user. small update~~
  > v2.4.3 2017-08-22
  - Knowing that comments will delete two characters at the same time, a new round of updates is about to start
  > v2.4.2 2017-06-04
  - Improve rwl-exempt, for the class containing "rwl-exempt", the js event will not be overwritten
  > v2.4.1 2017-05-20
  - Added "book.hjsm.tom.com; chuangshi.qq.com" to the blacklist, thanks to zhangbaida
  > v2.4.0 2017-05-18
  - Change the URL matching rules, if one (or more) level domain names are in the blacklist, then the multi-level domain names above it are also in the blacklist
  - The local data version is updated to 1.0, the storage is sorted by name, and the data is updated to 25 websites.
  > v2.3.0 2017-05-16
  - Update the local database and try to maintain a list of anti-copy websites. For elements containing rwl-exempt in the class, avoid killing. If your own script conflicts with it, please try to add "rwl-exempt" to the class of the element
  > v2.2.4 2017-05-15
  - Baidu Flower Language huayu.baidu.com, the original script is valid for this website, but mine has a problem. I use other methods to solve it temporarily, so I update the script separately to troubleshoot this problem in the future
  > v2.2.3 2017-05-15
  - Fix the problem that the vertical and horizontal, starting point has no marquee
  > v2.2.2 2017-05-07
  - Added clear mousedown and mouseup events to the default rules
  > v2.2.1 2017-05-02
  - Change the name; change the icon; fix the style; remove the news sharing of Fenghuang.com;
  > v2.2.0 2017-04-26
  - Modify some illogical places in the original 2.1 revision
  > v2.1.6 2017-04-26
  - Adjust the z-index to the maximum value; insert directly into the end of the html on a webpage without a body element; add an icon
  > v2.1.5 2017-04-25
  - Individual websites are overlaid with transparent layers to prevent copying
  > v2.1.4 2017-04-24
  - Comment out console.log
  > v2.1.3 2017-04-24
  - Add basic style appearance
  > v2.1.2 2017-04-07
  - 2.1.2 Fix the problem that iframe is also displayed
  > v2.1.1 2017-03-31
  - Style modification style fix
  > v2.1.0 2017-03-30

  > v2.1.0 2017-03-30
  - big change, big change
  > v2.0.1 2017-03-29

  > v2.0.1 2017-03-29

  > v2.0.0 2017-03-28
