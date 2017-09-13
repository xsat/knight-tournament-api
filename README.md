## Database sructure

```
user
user_id
name
email
password
```

```
access_token
access_token_id
user_id
token
expiry_date
```

```
model
model_id
name
description
```

```
player
player_id
user_id
model_id
name
```

```
action
action_id
name
description
```

```
game
game_id
status
started_date
ended_date
```

```
play
play_id
game_id
player_id
status
```

```
position
position_id
x
y
```

```
turn
turn_id
position_id
action_id
player_id
game_id
added_date
```
