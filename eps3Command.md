client.on('message', msg => {
  if (!msg.content.startsWith(prefix)) return
  let args = msg.content.split(" ").slice(1)
  args = msg.content.slice(prefix.length).split(/ +/);
  let command = msg.content.split(" ")[0];
  command = command.slice(prefix.length);
  command = args.shift().toLowerCase();
})
