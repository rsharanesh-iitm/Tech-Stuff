## Ever wondered how does the processor of any computer or phone works?
***Let's first look at what is a processor?***
A processor, or "microprocessor," is a small chip that resides in computers and other electronic devices. Its basic job is to receive input and provide the appropriate output. While this may seem like a simple task, modern processors can handle trillions of calculations per second. The central processor of a computer is also known as the CPU, or "central processing unit." This processor handles all the basic system instructions, such as processing mouse and keyboard input and running applications. The term processor is interchangably used for the word CPU, but it's not the only processor in the system there's also GPU that is used a processor to handle graphics.

***If so then what is a CPU core or a core in the CPU?***
A core, or CPU core, is the "brain" of a CPU. It receives instructions, and performs calculations, or operations, to satisfy those instructions. A CPU can have multiple cores.

Each core of a CPU can perform operations separately from the others. Or, multiple cores may work together to perform parallel operations on a shared set of data in the CPU's memory cache (Cache is a high-speed access area that can be a reserved section of main memory or on a storage device).

***What are threads?***
Threads are the virtual components or codes, which divides the physical core of a CPU into virtual multiple cores. A single CPU core can have up-to 2 threads per core.
For example, if a CPU is dual core (i.e., 2 cores) it will have 4 threads. And if a CPU is Octal core (i.e., 8 core) it will have 16 threads and vice-versa.

The thread is created by a process. Every time you open an application, it itself creates a thread which will handle all the tasks of that specific application. Like-wise the more application you open more threads will be created.The threads are always created by the operating system for performing a task of a specific application.
There is single thread (code of that core which performs the computations also known as primary thread) on the core which when gets the information from the user, creates another thread and allocates the task to it. Similarly, if it gets another instruction it forms second thread and allocates the task to it. Making a total of two threads.

***Clock speed in CPU***
Clock speed is another number that’s highly advertised with CPUs — the “gigahertz” (GHz) figure quoted on product listings. It effectively denotes how many instructions a CPU can handle per second, but that’s not the whole picture regarding performance. Clock speed mostly comes into play when comparing CPUs from the same product family or generation. When all else is the same, a faster clock speed means a faster processor, but a 3GHz processor from 2010 isn’t going to be as fast as a 2GHz processor from 2018. There is a drastic improvement in the technology and so their performance also increases exponentially.

***What about GPU?***
This processor is specifically designed for rendering graphics that are output on a monitor. Desktop computers often have a video card that contains the GPU, while mobile devices usually contain a graphics chip that is integrated into the motherboard. By using separate processors for system and graphics processing, computers are able to handle graphic-intensive applications more efficiently.

***Basic elements of a CPU***
1. _Arithmetic logic unit (ALU)_, which carries out arithmetic and logic operations on the operands in instructions. 
2. _Floating point unit (FPU)_, also known as a math coprocessor or numeric coprocessor, a specialized coprocessor that manipulates numbers more quickly than the basic microprocessor circuitry can. It mostly concentrates on the mathematical computation involving floating point numbers.
3. _Registers_, which hold instructions and other data. Registers supply operands to the ALU and store the results of operations.
4. _L1 and L2 cache memory_, their inclusion in the CPU saves time compared to having to get data from random access memory (RAM).(Level 1 caching is also referred to as L1 cache, primary cache, internal cache, or system cache. With computer processors, L1 cache is cache built into the processor that is the fastest and most expensive cache in the computer. The L1 cache stores the most critical files that need to be executed and is the first thing the processor looks when performing an instruction. On the other hand Level 2 cache or the L2 cache is located very close to the CPU but not exactly within the CPU, they perform some secondary tasks.)

***Functions performed by the CPU***
The four primary functions of a processor are fetch, decode, execute and write back.
1. Fetch- is the operation which receives instructions from program memory from a systems RAM.
2. Decode- is where the instruction is converted to understand which other parts of the CPU are needed to continue the operation. This is performed by the instruction decoder
3. Execute- is where the operation is performed. Each part of the CPU that is needed is activated to carry out the instructions.
4. Write back- is where the output operation is performed. In this step the output of the initiated process is being sent back to the user.


***Types***
Most processors today are multi-core, which means that the IC contains two or more processors for enhanced performance, reduced power consumption and more efficient simultaneous processing of multiple tasks (parallel processing). Multi-core set-ups are similar to having multiple, separate processors installed in the same computer, but because the processors are actually plugged into the same socket, the connection between them is faster. 

Most computers may have up to two-four cores; however, this number can increase up to 12 cores, for example. If a CPU can only process a single set of instructions at one time, then it is considered as a single-core processor. If a CPU can process two sets of instructions at a time it is called a dual-core processor; four sets would be considered a quad-core processor. The more cores, the more instructions at a time a computer can handle.

Finally let's look at

***How are processors selected up?***
A processor performance mostly depends on two specifications; the number of cores and the clock speeds it has to offer. Let’s explore how to go about choosing one based on these two numbers:

1. A core is an element of the processor that implements and executes tasks. Gadgets today, come with multiple cores. Each core is designed to handle and execute tasks. More the number of cores, more and heavier apps it can perform simultaneously. Most commonly found are dual-core (two), quad-core (four) and octa-core (eight), with the latter being the most powerful. Some processors also come with hexa-core (six), but they are pretty rare.
2. Processors are also defined by their clock speeds, which is mentioned in Gigahertz (GHz). This often refers to the speeds at which each of the cores can perform tasks. Naturally, higher the number, better the performance. However, you might find multiple GHz numbers for multi-core processors, even on some high-end variants. That’s because most manufacturers try to create a balance between power and efficiency. For example, Qualcomm’s new Snapdragon 845 chipset features eight cores, four of which are clocked at 2.8GHz to deliver peak performance, and four are clocked at 1.7GHz, for delivering efficiency and consuming less battery.

So, blindly just following the number of cores doesn't help in deciding the best processor, we must also look at the clock speed at which they work while choosing the best processor. 

Also the interesting thing to be noted here is that both our smartphones as well as the computer are made up of the processors, but they aren't the same even though they perform the same task. Let's have a look at them now,

***Mobile processor vs computer processor***
Both computers and smartphones are marketed heavily by their processor, and while the function is the same - both allow the individual devices to work - there are two major differences:

1. When processors run they generate heat. Lots of heat. Because mobile devices are considerably smaller than computers, the heat generated by a running mobile processor is often amplified and can seriously harm components, or even melt them. Therefore, the developers and designers of the devices limit, or throttle, the speed at which a mobile processor can run. This means that if a processor is getting hot, it will limit its speed, which equates to slower performance.Because of this throttling, the processor on many phones will actually run slower than the advertised speed. In fact, the advertised speed of mobile processors is normally the maximum. Compare this to most computer processors, where the advertised speed is usually the average running speed, and you begin to see why computers are more powerful.

2. The second big difference is connected with performance. If you take a computer and compare it to a mobile device with the same speed of processor, the computer will usually be able to do more. This is because the processor is limited in what it can do by the other hardware components, like the RAM, Graphics Processing Unit, etc. Computers have more space, so they can fit more advanced components, and are consequently able to do more. Also the computer processors do have a larger number of CPU cores when compared to the mobile processors. So as per the general rule, when the number of cores increases parallely the performance also increases.


