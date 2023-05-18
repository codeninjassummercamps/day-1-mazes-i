# Day 1 Mazes I

## Mazes I

In this activity, you will learn about Sequences by writing code to get the agent through a maze.

## Listen to Sensei!

Make sure you are listening and following along to your Senseis' instructions!

## You Did It!

Good job following along with Sensei! Make sure your code is correct by looking at the Sensei's board, then try making your own maze!
Can you make the agent navigate your custom maze?

```blocks
player.onChat("agent", function () {
    agent.teleport(pos(0, 0, 0), orientation.West)
})
player.onChat("maze", function () {
    agent.move(FORWARD, 1)
    agent.turn(TurnDirection.Right)
})
```
