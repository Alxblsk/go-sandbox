# Dear Diary,

Learning new programming language is a routine that requires patience and everyday progress. I'm sharing my everyday progress with you to make sure I'm not stagnating and leaving this activity at the beggining of journey.

## Day 1.

Earlier I started learning `Go In Practice` and even finished with the first chapter, but then left this book waiting for me for better times. The time has come and I blown dust off a book today and finished reading the second chapter. It covered flags, commands, configurations and some example of working with a simple web server. That was pretty interested, but I noticed that I lacked information about types, scopes and syntax overall. So I spent 2 minutes in Twitter to find some neat courses and chosen have chosen [Ednsquare | Learn Go](https://ednsquare.com/story/learn-go-beginners-guide-to-learn-golang-from-scratch-------gTmFx6) as a starting point. Read an introduction, then tried an example from the book, just typed and checked it. That's weird sometimes, but at least I noticed things I need to clarify.

## Day 2.

I decided to continue with `Learn Go` course first and cover `Variables, Types and Scopes` part. Everything is clear and rarely there are common things with JS. This is good, this is why I'm here, to notice as much differences as I can.

More I read `Go In Practice`, more I see that this is not a book for total newcomers in the language. Well, OK. Not a problem. There is no need to set a goal and understand absolutely everything. Today's chapter, `Parallel Calculations` explained an interesting concept of `Mutex`, which allows to lock/unlock structures (to avoid simultaneous access if prohibided). Continuing this topic, it was great to read about a concept of Channels (with their weird new syntax, `<-`). Going to try couple of examples with those mechanisms later today.

## Day 3.

It became obvious that support the same pace is hard. However, I've found some time for reading and read about conditionals and loops in Go. Nothing really special except an absence of while cycle, which can be replaced with `for`. Neat.

Spent 10 minutes on a book as well, reading about error handling. 

# Day 4. 

Decided not to leave this important thing as learning for an evening and got a portion of information at the morning. This time `Functions` and error handling in Go. Funny that golang considers using `Errors` as controlled exceptions, handled by developer, and `Panics` (e.g. crashes) as runtime unpredictable errors. I like this division, together with multiple returns it sounds super comfortable. In Javascript, similar thing with having a separate variable is widely used in Node.js (by using a callback with multiple arguments). But Go type of solution sounds more elegant.
