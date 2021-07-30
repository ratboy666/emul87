# emul87

Here is a rare oddity. In 1985, I wrote an application that used floating point math. In PASCAL. I used Turbo Pascal, and used the 8087 variant. The application was commerically successful. I had a sales person, who purchased a 286 based laptop/luggable in 1987 to demonstrate the application. The problem was that the laptop did not have a socket for a 287.

I spent a weekend, and cooked up EMUL87. Emulated an 8087 for Turbo Pascal, and quite a few other programs. I used the (at the time) new Borland Turbo C, which had a 8087 floating point software library. Turning on instruction trapping on the 286/386, and vectoring to the appropriate Turbo C run-time function made short work of problem.

I then released the software to the public. The source? Sorry, long gone. But it was trivial. Since it only took a weekend the first time, and it wasn't very long, it could be regenerated if needed.

Put on github for the historical record.

Fred Weigel
