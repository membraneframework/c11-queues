# Lock-free Single-Producer Single-consumer (SPSC) queue

## Design decissions

 - Static indexed ring buffer or dynamically linked-lists?

## Some reading material

- http://moodycamel.com/blog/2013/a-fast-lock-free-queue-for-c++
- https://github.com/cameron314/readerwriterqueue
- http://www.1024cores.net/home/lock-free-algorithms/queues/unbounded-spsc-queue
- https://software.intel.com/en-us/articles/single-producer-single-consumer-queue
- http://www.boost.org/doc/libs/1_61_0/doc/html/boost/lockfree/spsc_queue.html
- https://github.com/mstump/queues
- http://psy-lob-saw.blogspot.ca/p/lock-free-queues.html
- http://calvados.di.unipi.it/storage/talks/2012_SPSC_Europar.pdf

## Credits

- Umar Farooq
- Steffen Vogel <post@steffenvogel.de>

## License

#### BSD 2-Clause License

All rights reserved.

 - Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
 - Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
 - Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

```
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```