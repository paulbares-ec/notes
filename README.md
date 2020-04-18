# Personnal notes

* [Rust](https://github.com/azeq/notes/blob/master/rust.md)
* [Linux](https://github.com/azeq/notes/blob/master/linux.md)

# Misc.
- Task queue:
  - https://slack.engineering/scaling-slacks-job-queue-687222e9d100 tags{redis,kafka}
  - https://redis.io/commands/rpoplpush 
    > ...queue is not reliable as messages can be lost, for example in the case there is a network problem or if the consumer crashes just after the message is received but it is still to process.
RPOPLPUSH (or BRPOPLPUSH for the blocking variant) offers a way to avoid this problem: the consumer fetches the message and at the same time pushes it into a processing list. 
