# Watney OP Help

### !karma -ban @user

### !karma -bans

### !karma -unban @user

### ?term -set [new description]

### !ops

### !op @user

### !deop @user

### !pause @botname

Keep the bot from taking or responding to input. Commands can be flagged to ignore paused status, but should only be used in special circumstances.

### !unpause @botname
### !play @botname

Let the bot go back to normal input and response.


### !raffle -create {description}

Create a new raffle if there is not an active one already. Use `!raffle -reset` to clear the current raffle.

### !raffle -update {description}

### !raffle -cooldown {cooldown}

Sets the cooldown for how often a user can get another ticket, in minutes.  Set to -1 to only allow one ticket per member.

### !raffle -reset

Clear the current raffle and tickets issued. Be careful, cannot be undone.

### !raffle -pick

Pick a random ticket.  Does not do anything with the tickets, can be used as many times as you need.  Does not exclude previous winners.


