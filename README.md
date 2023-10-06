# بوت سستم كل الحقوق لـ0.3d discord 

بوت سستم كل الحقوق لـ0.3d discord 
لا تلعب باي كود عشان ما يخرب عليك البوت او البروجيkت
_____________ اشياء مهمه__________

const prefix = "حط مثل - او !"//برفكس حقك
client.on("ready", () => {
  client.user.setActivity(`03d`)//حالة البوت

_____________ رد تلقائي + مش مهم مره _____________

client.on('message', msg => {
  if (msg.content === 'هلا') {
    msg.reply('هلا بيك عمري ');

client.on('message', msg => {
  if (msg.content === 'ارحب') {
    msg.reply('البقى');

client.on('message', msg => {
  if (msg.content === 'سلام عليكم') {
    msg.reply('وعليكم السلام حبي نورت/ي');

	______ الاوامر المهمه ______

  {

       })
       
          })
          })
   }
  });




//lock
client.on("message",message =>{
let command = message.content.toLowerCase().split(" ")[0];
if (command == `${prefix}lock` || command == `${prefix}lc` || command == `lock`) {
        let lockPermErr = new Discord.MessageEmbed()
        .setTitle("**User Permission Error!**")
        .setDescription("**لا يمكنك ذالك نعتذر..❌**")
        if(!message.channel.permissionsFor(message.member).has("MANAGE_CHANNELS") ) return message.channel.send(lockPermErr);

        let channel = message.channel;


                    SEND_MESSAGES: false,
                    ADD_REACTIONS: false
                });
            });
        } catch (e) {
            console.log(e);
        }

        message.channel.send(`تم قفل بنجاح..🔒`);
    }
     }); 
