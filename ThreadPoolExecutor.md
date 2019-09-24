## Java中线程池类型及原理
#### 一、为什么要用线程池
减少每次创建线程，销毁线程开销，
提高响应速度，
提高线程可管理性。
### 二、Executor接口
Executor框架中的所有类可以分为三大类：
1：任务，任务有两种类型：Runnable和Callable
2: 任务执行器
  2.1：Executor框架最核心的接口是Executor,它表示任务的执行器。
  2.2：Executor的子接口是ExecutorService
      2.2.1:ExecutorService有两大实现类：ThreadPoolExecutor和ScheduleThreadPoolExecutor
3: 执行结果
future接口表示异步执行的结果，它的实现类为futureTask。
### 四种类型的线程池
 1.1: FixedThreadPool 固定大小的线程池，
 1.2：CachedThreadPool 可缓存线程池
 1.3：SingleThreadExecutor单一线程池
 1.4：ScheduledThreadPool 可调度的线程池
