```}else if (command  == "forward") {
  bot.setControlState('forward', true)
  const MoForw = new D.MessageEmbed()
      .setDescription(`:white_check_mark: Im Moving forward To Stop Do -stop`)
      .setColor(color)
  msg.channel.send(MoForw)
}else if (command  == "backward") {
  bot.setControlState('back', true)
  const MoBackw = new D.MessageEmbed()
      .setDescription(`:white_check_mark: Im Moving backward To Stop Do -stop`)
      .setColor(color)
  msg.channel.send(MoBackw)
}else if (command  == "stop") {
  bot.clearControlStates()
  const MoStop = new D.MessageEmbed()
      .setDescription(`:white_check_mark: Stopped!`)
      .setColor(color)
  msg.channel.send(MoStop)
}else if (command  == "left") {
  bot.setControlState('left', true)
  const MoLeft = new D.MessageEmbed()
      .setDescription(`:white_check_mark: Im Moving left To Stop Do -stop`)
      .setColor(color)
  msg.channel.send(MoLeft)
}else if (command  == "right") {
  bot.setControlState('right', true)
  const MoRight = new D.MessageEmbed()
      .setDescription(`:white_check_mark: Im Moving Right To Stop Do -stop`)
      .setColor(color)
  msg.channel.send(MoRight)
}
```
