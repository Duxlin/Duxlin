- 👋 Hi, I’m Mr.Kanambo
- 👀 I’m interested in programming, hacking, mobile development, cyber security, networking, web design
- 🌱 I’m currently learning programming and networking
- 💞️ I’m looking to collaborate on ... hacking, programming, mobile app development and cyber security
- 📫 How to reach me ... folorunshoabdulquodir1@gmail.com

<!---
Duxlin/Duxlin is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/**
   * Create By Dika Ardnt.
   * Contact Me on wa.me/6288292024190
   * Follow https://github.com/DikaArdnt
*/

const fs = require('fs')
const chalk = require('chalk')

// Website Api
global.APIs = {
	zenz: 'https://zenzapis.xyz',
}

// Apikey Website Api
global.APIKeys = {
	'https://zenzapis.xyz': 'Your Key',
}

// Other
global.owner = ['254114148625']
global.premium = ['254114148625']
global.packname = 'Mr.kanambo #0059C5bot'
global.author = 'WhatsApp Bot'
global.sessionName = 'hisoka'
global.prefa = ['','!','.','🐦','🐤','🗿']
global.sp = '⭔'
global.mess = {
    success: '✓ Success',
    admin: 'Special features admin group!',
    botAdmin: 'The Bot must be an Admin first!',
    owner: 'Special Owner Bot Features',
    group: 'Features used Only for Group!',
    private: 'Features used only for Private Chat!',
    bot: 'Special features of Bot Number Users',
    wait: 'Loading...',
    endLimit: 'Your Daily Limit Has Been Exhausted, The Limit Will Be Reset Every 12 Hours',
}
global.limitawal = {
    premium: "Infinity",
    free: 100
}
global.thumb = fs.readFileSync('./lib/hisoka.jpg')
global.visoka = { url: 'https://telegra.ph/file/15209657f9d4f59c7ca1e.mp4' }

let file = require.resolve(__filename)
fs.watchFile(file, () => {
	fs.unwatchFile(file)
	console.log(chalk.redBright(`Update'${__filename}'`))
	delete require.cache[file]
	require(file)
})
