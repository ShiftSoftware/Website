We use a centralized Collaboration tool. And it's in our company's culture to make sure that **all** of our work is recorded and progressed in the task management system.  

We want our work to be organized, categorized, and accessible to all relevant parties. Having a centralized collaboration tool solves below problems:

* Not everyone is able to attend all meetings or join all phone calls.
* Details discussed in meetings & phone calls can be forgotten.
* Discussions in Chat Apps & Emails might not be accessible by everyone needing them. Or they might be easily lost in long threads.

Below is our strategy for organizing our work into tasks:

## <span style="font-weight:400;">Work Breakdown</span>
We breakdown any given work to the smallest possible **unit of work**. The work units are organized into tasks and sub-tasks.  

We follow the below simple rule of thumb for knowing when to stop the breakdown:  
!!! info "When to Stop"
	Can the work be explained in a few short (and meaningful) English sentences? 
	
	* **No**: Then keep breaking down.
	* **Yes**: The unit of work can be recorded as a task or sub-task


## <span style="font-weight:400;">Version Control (git)</span>
Tasks are not only the smallest **unit of work**. When each task is completed, a **commit** is made in the Version Control.  

We follow the below simple guideline:

* Every commit has a corresponding Task.
* A commit message consists of a Task ID, followed by a colon, then followed by the task title. eg: `#301uqa7: Change date format to 'yyyy-MM-dd'`

!!! info "Continuous Integration"
	The fact that work is broken down to the smallest possible unit and the one-to-one relation between a task and a commit, forces every commit to also be very small.  
	This is naturally enabling the practice [Continuous Integration](continuous-integration.md)


## <span style="font-weight:400;">Time Tracking</span>
Most Collaboration tools, including the one we're using provide an easy way to track and record time. We make it a habit to always start the timer on the Task at hand. 

## <span style="font-weight:400;">Reporting</span>
One more advantage of breaking down work in an organized manner and giving them meaningful task titles is that work reports can be easily generated and shared with clients and stakeholders.
