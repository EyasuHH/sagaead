# Write-up Questions

1. **Who and what did you find helpful for this project?**
-------

    Organized linkedList by referring to tutorialspoint for the linkedlist class and nodes

    Codereview

2. **How did you test that your stack implementations were correct?**
------

    Switching the list for sampling values of the .dat file

3. **Did you use any classes fromthe Java framework or other class library?**
--------

    Used java.util.EmptyStackException library

4. **For  a  .dat  file  with  1  million  lines,how  many times would this resizing occur? What about with 1 billion or 1 trillion?**
  --------
    1 mil: 1000, 1 bil: 10000, 1 tril: 100000
    
    
5. **Instead of a DStack interface, pretend you were given a fully-functional FIFO Queue class. How might you implement this project**
    **with one or more instances of a FIFO Queue**
   
   
   
6. **Write pseudocode for your push and pop operations. Assume your Queue class provides the operations enqueue, dequeue, isEmpty, &size.**
    
    public double pop() 
    
		if isEmpty()
		
			isEmpty.enqueue 
			
		else
		
			isEmpty.dequeue
			
			size *= 10 
			
			return x
		

7. **Why would a stack implementation using a queue, as you described in the previous problem**

	**be worse than your array and linked-liststack implementations?**
	
	
	The order of the stack when using linkedlist is kept in order while the queue does not work the same way
