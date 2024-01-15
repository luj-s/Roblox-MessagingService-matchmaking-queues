# Roblox MessagingService matchmaking queues
Simple global MessagingService matchmaking system with queues.

# Usage
To use this module into your Roblox game, simply download ![Queues.rbxm](Queues.rbxm?raw=true "Queues.rbxm"), insert the [model](https://create.roblox.com/marketplace/asset/15528670427) or import the 
[package](https://create.roblox.com/marketplace/asset/15528694525). 

# API

## Functions

### Ready
Tells the server to look for an available queue and join it, or make a new one.

### Unready
Tells the server to make the client leave the queue it is in.

## Events

### ClientJoinedQueue -> QueueAccessCode: string
Fires when the client joined a queue, returning its access code.

### PlayerJoinedQueue -> PlayerUserId: number
Fires when a player joins the client's queue, returning his UserId.

### PlayerLeftQueue -> PlayerUserId: number
Fires when a players leaves the client's queue, returning his UserId.

### GameStarting -> void
Fires when the client's queue starts teleporting players to the game place.
