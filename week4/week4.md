# Week 4

## BitMap

SETBIT KEY OFFSET VALUE

GETBIT KEY OFFSET

BITCOUNT KEY (number of 1 on bitmaps)

BITFIELD KEY (SET|GET|INCRBY) (i5|u5) OFFSET VALUE

encoding raw

BITOP (OR|AND|XOR) NEWKEY KEY1 KEY2

## PUB/SUB

PUBLISH channel message
SUBSCRIBE channel
UNSUBSCRIBE channel

- fire and forget

PSUBSCRIBE pattern
PUNSUBSCRIBE patter

PUBSUB subcommand argumment

- channels
- numsub
- numpat
