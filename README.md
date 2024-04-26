# 𝗡𝗘𝗫𝗧𝗚𝗘𝗡 - 𝗕𝗢𝗧𝗣𝗔𝗖𝗞
### Thank you for using my botpack file

Page: [https://www.facebook.com/nextgen.project1](https://www.facebook.com/nextgen.project1?mibextid=ZbWKwL)

Group: [https://www.facebook.com/groups/3789457821285570](https://www.facebook.com/groups/3789457821285570/?ref=share)

__Before you start, please read through my details to know what features are available__

Choose from the latest html versions 
It's in the posts on my fb group or page

then go to config.json type value version to change and restart the console
[Open config.json](./config.json)
<details>
  <summary>About Website</summary>
  <h1>Website</h1>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-25-03-27-08-99_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

<details>
  <summary>LoginAcc</summary>
  <h1>Website</h1>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-19-24-48-61_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

<details>
  <summary>ConsoleWeb</summary>
  <h1>Website</h1>
  
  [Open config.json](./config.json)
 
  Just choose whether you are off or on
  If on the website, file is running 
  If off in the main/origin running file in the console
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-19-24-53-43_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

<details>
  <summary>Cmd&Event</summary>
  <h1>Cmd And Event</h1>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-25-03-27-05-42_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

<details>
  <summary>Config Edit</summary>
  <h1>Website</h1>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-19-25-03-15_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

<details>
  <summary>ConfigFca Edit</summary>
  <h1>Website</h1>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-19-25-09-77_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

<details>
  <summary>AdminList display</summary>
  <h1>Website</h1>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-19-25-21-42_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>

# NEXT ABOUT FILE SYSTEM
<details>
  <summary>Encypted Appstate&Token</summary>
  They won't be able to leak the appState and token if you replace the new appstate on the website login make sure you don't have 2fa acc
   <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-25-02-55-23-78_dce875ef40efa4e902b2719365b6f678.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>
<details>
  <summary>Improve handleDatabase</summary>
  He is now fixed when pushing to the user database and we can see the list users and groups in the console
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-20-32-57-08_dce875ef40efa4e902b2719365b6f678.jpg" alt="Background 1" style="width: 150px; height: 300px;">
</details>
<details>
<summary>New add Obj</summary>
  botId - to get id from your bot
  <pre><code class="language-javascript">const id = await botId();
  </code></pre>
  
  cookies - so you can see whole cookies 
  <pre><code class="language-javascript"> const cs = await cookies();
  </code></pre>
  token - so you can see the token
  <pre><code class="language-javascript">const tk = await token();
  </code></pre>
  getId - to get link fb to fbid
  <pre><code class="language-javascript">const result = await getId(id);
  </code></pre>
  stalk - stalk user fb graph
  <pre><code class="language-javascript">const result = await stalk(id)
  </code></pre>
  
  <h1>On Cmds</h1>
  <pre><code class="language-javascript">module.exports.run = function({ api, event, args, models, Users, Threads, Currencies, permssion, botId, cookies, token, getID, stalk})
  </code></pre>

  <h1>On Events</h1>
  <pre><code class="language-javascript">module.exports.run = async function ({ api, event, botId, cookies, token, getID, stalk })
  </code></pre>

</details>

<details>
  <summary>Cron Schedule scripts</summary>
  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-25-01-46-50-96_dce875ef40efa4e902b2719365b6f678.jpg" alt="Background 1" style="width: 150px; height: 300px;">

setup like this 
Visit their website first so you can know the desired or setup time in cron
Website: [https://crontab.guru](https://crontab.guru/#*/1_*_*_*_*)

<img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-25-02-48-45-30_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">

<h1>text</h1>
  <pre><code class="language-javascript">const fs = require('fs');
    const request = require('request');
    const cron = require('node-cron');
    module.exports = function ({ api, botmodels }) {
      cron.schedule('*/1 * * * *', async () => {
        try {
          const list = await api.getThreadList(100, null, ["INBOX"]);
          list.forEach(thread => {
            if (thread.isGroup && thread.threadID != list.threadID) {
    api.sendMessage("hello", thread.threadID)
          });
        } catch (err) {
          console.error('Error in text cron job:', err);
        }
      }, {
        scheduled: true,
        timezone: "Asia/Manila"
      });
    };
  </code></pre>

  <h1>audio</h1>
  <pre><code class="language-javascript">const fs = require('fs');
    const request = require('request');
    const cron = require('node-cron');
    module.exports = function ({ api, botmodels }) {
      cron.schedule('*/1 * * * *', async () => {
        try {
          const list = await api.getThreadList(100, null, ["INBOX"]);
          list.forEach(thread => {
            if (thread.isGroup && thread.threadID != list.threadID) {
              const link = "https://drive.google.com/uc?id=1ilSBkrxlpRAZiHGdnuqFhYAloEsqmYTP";
              const callback = () => {
                api.sendMessage({
                  body: 'Check out this audio!',
                  attachment: fs.createReadStream(__dirname + "/audio.mp3")
                }, thread.threadID, () => fs.unlinkSync(__dirname + "/audio.mp3"));
              };
              request(encodeURI(link)).pipe(fs.createWriteStream(__dirname + "/audio.mp3")).on("close", callback);
            }
          });
        } catch (err) {
          console.error('Error in audio cron job:', err);
        }
      }, {
        scheduled: true,
        timezone: "Asia/Manila"
      });
    };
  </code></pre>

  <h1>video</h1>
  <pre><code class="language-javascript">const fs = require('fs');
    const request = require('request');
    const cron = require('node-cron'); 
    module.exports = function ({ api, botmodels }) {
      cron.schedule('*/1 * * * *', async () => {
        try {
          const list = await api.getThreadList(100, null, ["INBOX"]);
          list.forEach(thread => {
            if (thread.isGroup && thread.threadID != list.threadID) {
              const link = "https://drive.google.com/uc?id=1cU1QQ3W1fYO5tjvxYo8lFAyjZ4Bel1xQ";
              const callback = () => {
                api.sendMessage({
                  body: 'Check out this video!',
                  attachment: fs.createReadStream(__dirname + "/video.mp4")
                }, thread.threadID, () => fs.unlinkSync(__dirname + "/video.mp4"));
              };
              request(encodeURI(link)).pipe(fs.createWriteStream(__dirname + "/video.mp4")).on("close", callback);
            }
          });
        } catch (err) {
          console.error('Error in video cron job:', err);
        }
      }, {
        scheduled: true,
        timezone: "Asia/Manila"
      });
    };
  </code></pre>

  <h1>image</h1>
  <pre><code class="language-javascript">const fs = require('fs');
    const request = require('request');
    const cron = require('node-cron');
    module.exports = function ({ api, botmodels }) {
      cron.schedule('*/1 * * * *', async () => {
        try {
          const list = await api.getThreadList(100, null, ["INBOX"]);
          list.forEach(thread => {
            if (thread.isGroup && thread.threadID != list.threadID) {
              const link = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRky365Df5u_CCvDCNpH24mp1aOLJ4jvIUqCEWwYoXhbIz1nBxSSbUbJd0&s=10";
              const callback = () => {
                api.sendMessage({
                  body: 'Son Goku!',
                  attachment: fs.createReadStream(__dirname + "/text.jpg")
                }, thread.threadID, () => fs.unlinkSync(__dirname + "/text.jpg"));
              request(encodeURI(link)).pipe(fs.createWriteStream(__dirname + "/text.jpg")).on("close", callback);
            }
          });
        } catch (err) {
          console.error('Error in text cron job:', err);
        }
      }, {
        scheduled: true,
        timezone: "Asia/Manila"
      });
    };
  </code></pre>
</details>

<details>
  <summary>Join & Leave - Noti</summary>
  We have real-time display of the background image. When a user leaves the group chat on Messenger, the bot automatically sends notifications to the users who left or joined the group.

  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-18-13-59-85_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 1" style="width: 150px; height: 300px;">

  <img src="https://raw.githubusercontent.com/ChoruTiktokers182/Features-nextgen/main/Screenshot_2024-04-24-18-14-05-19_40deb401b9ffe8e1df2f1cc5ba480b12.jpg" alt="Background 2" style="width: 150px; height: 300px;">
</details>
