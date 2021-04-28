
client.on("message", message => {

if (message.content === "!help") {
  const DM = message.author
  DM.send('Yes, I'm in your dms')
}

})
