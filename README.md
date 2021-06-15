Hi, I am @RopraMMC
I am working on a project with @TomDevGames
I am a student
I am curently doing multiple coding projects
I have little/base knowledge of code but have a more detailed easier way of interpreting things than others
I will spend months on a piece of code that won't even work (e.g:
    ##cmd cmds
@Bot.event
async def on_message(message, ctx, embed = discord.Embed(title="Commands/Help")):
    if message.content_startswith('-help', '-Help', '-HELP', '-HeLp', '-cmds', '-Cmds', '-Commands', '-commands', 'command', ' Command'):

        embed = discord.Embed(title="Commands/Help", value="Page 1", colour = 0xfffff)
        embed.add_field(name="-Ping", value="sends message containg the ping(ms) of the bot")
        embed.add_field(name="-8ball", value="gives a random awnser to the question attacted with the command")
        embed.add_field(name="-echo", value="echo's/relays the message given with the command")
        embed.add_field(name="-Hi", value= "says Hello to the user who gave the command")
        embed.add_field(name="-Purge", value= "Purges amount specified in command user sent (no purge limit)")
        embed.add_field(name="-Kick", value= "Kicks the mentioned user")
        embed.add_field(name="-Ban", value= "Bans the mentioned user")
        embed.add_field(name="-Unban", value="Unbans the mesntioned user (dont @ the person it wont work. You ahve to use their code)")
        embed.add_field(name="-rps", value="A Rock Paper Scissors game against me: DTG Bot, to use the -rps command do -rps (your choise)")
        embed.add_field(name='-invite', value='sends a link to invite me to other servers!')
        embed.add_field(name='-tictactoe', value="emulates a tictactoe game with the @'d users (e.g -tictactoe @Ropra#4091 @Discord#0001). To set your place do -place (your place (as a int.))")
        embed.add_field(name='-rr', value='Emulates a Russian Roulette game. A **33.33%** change to die.')
        embed.add_field(name='-ht', value='Emulates a Coin Flip game. A **50%** chance to get either.')
        embed.add_field(name='-beat', value="Beats the @'d user")
        embed.add_field(name='**calculator**', value='Emulates a calculator. -calculator is not a command However the calculator commands are: -+ (addition), -- (subtraction), -* (multiplication), -/ (division), -sqrt (square root)')
        embed.add_field(name='-dn', value='Sends cringy deez nuts jokes')
        embed.add_field(name='-suggest', value="Lets you suggest something and get other people's votes or opinions")
        embed.add_field(name='-l', value="Gives the @'d user an L")
        msg = await ctx.send(embed=embed)
        await msg.add_reaction('⬅️')
        await msg.add_reaction('➡️')
        
        def check(reaction, user):
            return user == message.author and str(reaction.emoji) == '➡️'
            embed1 = discord.Embed(Title='ye this doesnt matter', color=0xfffff)
            embed1.add_field(name='-dice', value='emulates a dice rolling.')
            embed1.add_field(name='-credit', value='Posts an embed with everyone that helped with this bot')
            await ctx.send(embed=embed1)
        
        def check2(reaction, user):
            return user == message.author and str(reaction.emoji) == '⬅️'
            embed3 = discord.Embed(title="Commands/Help", value="Page 1", colour = 0xfffff)
            embed3.add_field(name="-Ping", value="sends message containg the ping(ms) of the bot")
            embed3.add_field(name="-8ball", value="gives a random awnser to the question attacted with the command")
            embed3.add_field(name="-echo", value="echo's/relays the message given with the command")
            embed3.add_field(name="-Hi", value= "says Hello to the user who gave the command")
            embed3.add_field(name="-Purge", value= "Purges amount specified in command user sent (no purge limit)")
            embed3.add_field(name="-Kick", value= "Kicks the mentioned user")
            embed3.add_field(name="-Ban", value= "Bans the mentioned user")
            embed3.add_field(name="-Unban", value="Unbans the mesntioned user (dont @ the person it wont work. You ahve to use their code)")
            embed3.add_field(name="-rps", value="A Rock Paper Scissors game against me: DTG Bot, to use the -rps command do -rps (your choise)")
            embed3.add_field(name='-invite', value='sends a link to invite me to other servers!')
            embed3.add_field(name='-tictactoe', value="emulates a tictactoe game with the @'d users (e.g -tictactoe @Ropra#4091 @Discord#0001). To set your place do -place (your place (as a int.))")
            embed3.add_field(name='-rr', value='Emulates a Russian Roulette game. A **33.33%** change to die.')
            embed3.add_field(name='-ht', value='Emulates a Coin Flip game. A **50%** chance to get either.')
            embed3.add_field(name='-beat', value="Beats the @'d user")
            embed3.add_field(name='**calculator**', value='Emulates a calculator. -calculator is not a command However the calculator commands are: -+ (addition), -- (subtraction), -* (multiplication), -/ (division), -sqrt (square root)')
            embed3.add_field(name='-dn', value='Sends cringy deez nuts jokes')
            embed3.add_field(name='-suggest', value="Lets you suggest something and get other people's votes or opinions")
            embed3.add_field(name='-l', value="Gives the @'d user an L")
            await ctx.send(embed=embed3)
            )
            Yess it doesn't work and I spent about 2 months trying to make this code work. Yet my efforts were in vain. Good bye.
