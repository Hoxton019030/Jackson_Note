# Jackson Note

示範用的Json資料

```yaml
{
"threads": [
{
"threadName": "Reference Handler",
"threadId": 2,
"blockedTime": -1,
"blockedCount": 11,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 10,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "waitForReferencePendingList",
"fileName": "Reference.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.ref.Reference"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "processPendingReferences",
"fileName": "Reference.java",
"lineNumber": 253,
"nativeMethod": false,
"className": "java.lang.ref.Reference"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Reference.java",
"lineNumber": 215,
"nativeMethod": false,
"className": "java.lang.ref.Reference$ReferenceHandler"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "Finalizer",
"threadId": 3,
"blockedTime": -1,
"blockedCount": 28,
"waitedTime": -1,
"waitedCount": 29,
"lockName": "java.lang.ref.ReferenceQueue$Lock@44c7a61b",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 8,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "wait",
"fileName": "Object.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.Object"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "remove",
"fileName": "ReferenceQueue.java",
"lineNumber": 155,
"nativeMethod": false,
"className": "java.lang.ref.ReferenceQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "remove",
"fileName": "ReferenceQueue.java",
"lineNumber": 176,
"nativeMethod": false,
"className": "java.lang.ref.ReferenceQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Finalizer.java",
"lineNumber": 172,
"nativeMethod": false,
"className": "java.lang.ref.Finalizer$FinalizerThread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.lang.ref.ReferenceQueue$Lock",
"identityHashCode": 1153934875
}
},
{
"threadName": "Signal Dispatcher",
"threadId": 4,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 9,
"stackTrace": [],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "Attach Listener",
"threadId": 5,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "Common-Cleaner",
"threadId": 13,
"blockedTime": -1,
"blockedCount": 62,
"waitedTime": -1,
"waitedCount": 574,
"lockName": "java.lang.ref.ReferenceQueue$Lock@5cd912",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 8,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "wait",
"fileName": "Object.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.Object"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "remove",
"fileName": "ReferenceQueue.java",
"lineNumber": 155,
"nativeMethod": false,
"className": "java.lang.ref.ReferenceQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "CleanerImpl.java",
"lineNumber": 140,
"nativeMethod": false,
"className": "jdk.internal.ref.CleanerImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "InnocuousThread.java",
"lineNumber": 162,
"nativeMethod": false,
"className": "jdk.internal.misc.InnocuousThread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.lang.ref.ReferenceQueue$Lock",
"identityHashCode": 6084882
}
},
{
"threadName": "Monitor Ctrl-Break",
"threadId": 14,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": true,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read0",
"fileName": "SocketDispatcher.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.nio.ch.SocketDispatcher"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "SocketDispatcher.java",
"lineNumber": 46,
"nativeMethod": false,
"className": "sun.nio.ch.SocketDispatcher"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "tryRead",
"fileName": "NioSocketImpl.java",
"lineNumber": 261,
"nativeMethod": false,
"className": "sun.nio.ch.NioSocketImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implRead",
"fileName": "NioSocketImpl.java",
"lineNumber": 312,
"nativeMethod": false,
"className": "sun.nio.ch.NioSocketImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "NioSocketImpl.java",
"lineNumber": 350,
"nativeMethod": false,
"className": "sun.nio.ch.NioSocketImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "NioSocketImpl.java",
"lineNumber": 803,
"nativeMethod": false,
"className": "sun.nio.ch.NioSocketImpl$1"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "Socket.java",
"lineNumber": 966,
"nativeMethod": false,
"className": "java.net.Socket$SocketInputStream"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "readBytes",
"fileName": "StreamDecoder.java",
"lineNumber": 270,
"nativeMethod": false,
"className": "sun.nio.cs.StreamDecoder"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implRead",
"fileName": "StreamDecoder.java",
"lineNumber": 313,
"nativeMethod": false,
"className": "sun.nio.cs.StreamDecoder"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "StreamDecoder.java",
"lineNumber": 188,
"nativeMethod": false,
"className": "sun.nio.cs.StreamDecoder"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "InputStreamReader.java",
"lineNumber": 177,
"nativeMethod": false,
"className": "java.io.InputStreamReader"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "fill",
"fileName": "BufferedReader.java",
"lineNumber": 162,
"nativeMethod": false,
"className": "java.io.BufferedReader"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "readLine",
"fileName": "BufferedReader.java",
"lineNumber": 329,
"nativeMethod": false,
"className": "java.io.BufferedReader"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "readLine",
"fileName": "BufferedReader.java",
"lineNumber": 396,
"nativeMethod": false,
"className": "java.io.BufferedReader"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "AppMainV2.java",
"lineNumber": 49,
"nativeMethod": false,
"className": "com.intellij.rt.execution.application.AppMainV2$1"
}
],
"lockedMonitors": [
{
"className": "java.io.InputStreamReader",
"identityHashCode": 436417656,
"lockedStackDepth": 9,
"lockedStackFrame": {
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "read",
"fileName": "StreamDecoder.java",
"lineNumber": 188,
"nativeMethod": false,
"className": "sun.nio.cs.StreamDecoder"
}
},
{
"className": "java.io.InputStreamReader",
"identityHashCode": 436417656,
"lockedStackDepth": 12,
"lockedStackFrame": {
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "readLine",
"fileName": "BufferedReader.java",
"lineNumber": 329,
"nativeMethod": false,
"className": "java.io.BufferedReader"
}
}
],
"lockedSynchronizers": [
{
"className": "java.util.concurrent.locks.ReentrantLock$NonfairSync",
"identityHashCode": 866169291
}
],
"lockInfo": null
},
{
"threadName": "Notification Thread",
"threadId": 15,
"blockedTime": -1,
"blockedCount": 2,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 9,
"stackTrace": [],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "RMI TCP Accept-0",
"threadId": 17,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": true,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "Net.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.nio.ch.Net"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "NioSocketImpl.java",
"lineNumber": 755,
"nativeMethod": false,
"className": "sun.nio.ch.NioSocketImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocket.java",
"lineNumber": 675,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "platformImplAccept",
"fileName": "ServerSocket.java",
"lineNumber": 641,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocket.java",
"lineNumber": 617,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocket.java",
"lineNumber": 574,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "ServerSocket.java",
"lineNumber": 532,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "jdk.management.agent",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "LocalRMIServerSocketFactory.java",
"lineNumber": 52,
"nativeMethod": false,
"className": "sun.management.jmxremote.LocalRMIServerSocketFactory$1"
},
{
"classLoaderName": null,
"moduleName": "java.rmi",
"moduleVersion": "17.0.4.1",
"methodName": "executeAcceptLoop",
"fileName": "TCPTransport.java",
"lineNumber": 413,
"nativeMethod": false,
"className": "sun.rmi.transport.tcp.TCPTransport$AcceptLoop"
},
{
"classLoaderName": null,
"moduleName": "java.rmi",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "TCPTransport.java",
"lineNumber": 377,
"nativeMethod": false,
"className": "sun.rmi.transport.tcp.TCPTransport$AcceptLoop"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [
{
"className": "java.util.concurrent.locks.ReentrantLock$NonfairSync",
"identityHashCode": 1252929242
}
],
"lockInfo": null
},
{
"threadName": "RMI Scheduler(0)",
"threadId": 23,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 18,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@2c5cfad4",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 1170,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 899,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 744291028
}
},
{
"threadName": "mysql-cj-abandoned-connection-cleanup",
"threadId": 440,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 6460,
"lockName": "java.lang.ref.ReferenceQueue$Lock@2fffabd3",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "wait",
"fileName": "Object.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.Object"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "remove",
"fileName": "ReferenceQueue.java",
"lineNumber": 155,
"nativeMethod": false,
"className": "java.lang.ref.ReferenceQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "AbandonedConnectionCleanupThread.java",
"lineNumber": 91,
"nativeMethod": false,
"className": "com.mysql.cj.jdbc.AbandonedConnectionCleanupThread"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1136,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [
{
"className": "java.util.concurrent.ThreadPoolExecutor$Worker",
"identityHashCode": 251196488
}
],
"lockInfo": {
"className": "java.lang.ref.ReferenceQueue$Lock",
"identityHashCode": 805284819
}
},
{
"threadName": "Live Reload Server",
"threadId": 450,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": true,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "Net.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.nio.ch.Net"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "NioSocketImpl.java",
"lineNumber": 755,
"nativeMethod": false,
"className": "sun.nio.ch.NioSocketImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocket.java",
"lineNumber": 675,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "platformImplAccept",
"fileName": "ServerSocket.java",
"lineNumber": 641,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocket.java",
"lineNumber": 617,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocket.java",
"lineNumber": 574,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "ServerSocket.java",
"lineNumber": 532,
"nativeMethod": false,
"className": "java.net.ServerSocket"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "acceptConnections",
"fileName": "LiveReloadServer.java",
"lineNumber": 145,
"nativeMethod": false,
"className": "org.springframework.boot.devtools.livereload.LiveReloadServer"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": null,
"lineNumber": -1,
"nativeMethod": false,
"className": "org.springframework.boot.devtools.livereload.LiveReloadServer$$Lambda$1133/0x00000008015052e8"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [
{
"className": "java.util.concurrent.locks.ReentrantLock$NonfairSync",
"identityHashCode": 426207502
}
],
"lockInfo": null
},
{
"threadName": "DestroyJavaVM",
"threadId": 467,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": false,
"inNative": false,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "File Watcher",
"threadId": 982,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 34045,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "sleep",
"fileName": "Thread.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.Thread"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "scan",
"fileName": "FileSystemWatcher.java",
"lineNumber": 244,
"nativeMethod": false,
"className": "org.springframework.boot.devtools.filewatch.FileSystemWatcher$Watcher"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "FileSystemWatcher.java",
"lineNumber": 234,
"nativeMethod": false,
"className": "org.springframework.boot.devtools.filewatch.FileSystemWatcher$Watcher"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "Catalina-utility-1",
"threadId": 1827,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 28230,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@22845c06",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": false,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 1,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 1177,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 899,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 579099654
}
},
{
"threadName": "Catalina-utility-2",
"threadId": 1828,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 27535,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@22845c06",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": false,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 1,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "parkNanos",
"fileName": "LockSupport.java",
"lineNumber": 252,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "awaitNanos",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1672,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 1182,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 899,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 579099654
}
},
{
"threadName": "container-0",
"threadId": 1829,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 1816,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": false,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "sleep",
"fileName": "Thread.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.Thread"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "await",
"fileName": "StandardServer.java",
"lineNumber": 570,
"nativeMethod": false,
"className": "org.apache.catalina.core.StandardServer"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TomcatWebServer.java",
"lineNumber": 197,
"nativeMethod": false,
"className": "org.springframework.boot.web.embedded.tomcat.TomcatWebServer$1"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "HikariPool-4 housekeeper",
"threadId": 1831,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 752,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@3bb60700",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "parkNanos",
"fileName": "LockSupport.java",
"lineNumber": 252,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "awaitNanos",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1672,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 1182,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "ScheduledThreadPoolExecutor.java",
"lineNumber": 899,
"nativeMethod": false,
"className": "java.util.concurrent.ScheduledThreadPoolExecutor$DelayedWorkQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1001785088
}
},
{
"threadName": "File Watcher",
"threadId": 1833,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 34024,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "TIMED_WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "sleep",
"fileName": "Thread.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "java.lang.Thread"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "scan",
"fileName": "FileSystemWatcher.java",
"lineNumber": 250,
"nativeMethod": false,
"className": "org.springframework.boot.devtools.filewatch.FileSystemWatcher$Watcher"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "FileSystemWatcher.java",
"lineNumber": 234,
"nativeMethod": false,
"className": "org.springframework.boot.devtools.filewatch.FileSystemWatcher$Watcher"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "http-nio-8080-BlockPoller",
"threadId": 1834,
"blockedTime": -1,
"blockedCount": 253,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": true,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "wait",
"fileName": "WEPoll.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.nio.ch.WEPoll"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "doSelect",
"fileName": "WEPollSelectorImpl.java",
"lineNumber": 111,
"nativeMethod": false,
"className": "sun.nio.ch.WEPollSelectorImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "lockAndDoSelect",
"fileName": "SelectorImpl.java",
"lineNumber": 129,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "select",
"fileName": "SelectorImpl.java",
"lineNumber": 141,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "NioBlockingSelector.java",
"lineNumber": 313,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.NioBlockingSelector$BlockPoller"
}
],
"lockedMonitors": [
{
"className": "sun.nio.ch.Util$2",
"identityHashCode": 423306849,
"lockedStackDepth": 2,
"lockedStackFrame": {
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "lockAndDoSelect",
"fileName": "SelectorImpl.java",
"lineNumber": 129,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
}
},
{
"className": "sun.nio.ch.WEPollSelectorImpl",
"identityHashCode": 434056492,
"lockedStackDepth": 2,
"lockedStackFrame": {
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "lockAndDoSelect",
"fileName": "SelectorImpl.java",
"lineNumber": 129,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
}
}
],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "http-nio-8080-exec-1",
"threadId": 1835,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 18,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-2",
"threadId": 1836,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 19,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-3",
"threadId": 1837,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 18,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-4",
"threadId": 1838,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 19,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-5",
"threadId": 1839,
"blockedTime": -1,
"blockedCount": 1,
"waitedTime": -1,
"waitedCount": 17,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.management",
"moduleVersion": "17.0.4.1",
"methodName": "dumpThreads0",
"fileName": "ThreadImpl.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.management.ThreadImpl"
},
{
"classLoaderName": null,
"moduleName": "java.management",
"moduleVersion": "17.0.4.1",
"methodName": "dumpAllThreads",
"fileName": "ThreadImpl.java",
"lineNumber": 521,
"nativeMethod": false,
"className": "sun.management.ThreadImpl"
},
{
"classLoaderName": null,
"moduleName": "java.management",
"moduleVersion": "17.0.4.1",
"methodName": "dumpAllThreads",
"fileName": "ThreadImpl.java",
"lineNumber": 509,
"nativeMethod": false,
"className": "sun.management.ThreadImpl"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "getFormattedThreadDump",
"fileName": "ThreadDumpEndpoint.java",
"lineNumber": 51,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.management.ThreadDumpEndpoint"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "threadDump",
"fileName": "ThreadDumpEndpoint.java",
"lineNumber": 42,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.management.ThreadDumpEndpoint"
},
{
"classLoaderName": null,
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": null,
"lineNumber": -1,
"nativeMethod": false,
"className": "jdk.internal.reflect.GeneratedMethodAccessor354"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "invoke",
"fileName": "DelegatingMethodAccessorImpl.java",
"lineNumber": 43,
"nativeMethod": false,
"className": "jdk.internal.reflect.DelegatingMethodAccessorImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "invoke",
"fileName": "Method.java",
"lineNumber": 568,
"nativeMethod": false,
"className": "java.lang.reflect.Method"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invokeMethod",
"fileName": "ReflectionUtils.java",
"lineNumber": 282,
"nativeMethod": false,
"className": "org.springframework.util.ReflectionUtils"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "ReflectiveOperationInvoker.java",
"lineNumber": 77,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.endpoint.invoke.reflect.ReflectiveOperationInvoker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "AbstractDiscoveredOperation.java",
"lineNumber": 60,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.endpoint.annotation.AbstractDiscoveredOperation"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "handle",
"fileName": "AbstractWebMvcEndpointHandlerMapping.java",
"lineNumber": 305,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.endpoint.web.servlet.AbstractWebMvcEndpointHandlerMapping$ServletWebOperationAdapter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "handle",
"fileName": "AbstractWebMvcEndpointHandlerMapping.java",
"lineNumber": 388,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.endpoint.web.servlet.AbstractWebMvcEndpointHandlerMapping$OperationHandler"
},
{
"classLoaderName": null,
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": null,
"lineNumber": -1,
"nativeMethod": false,
"className": "jdk.internal.reflect.GeneratedMethodAccessor353"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "invoke",
"fileName": "DelegatingMethodAccessorImpl.java",
"lineNumber": 43,
"nativeMethod": false,
"className": "jdk.internal.reflect.DelegatingMethodAccessorImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "invoke",
"fileName": "Method.java",
"lineNumber": 568,
"nativeMethod": false,
"className": "java.lang.reflect.Method"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doInvoke",
"fileName": "InvocableHandlerMethod.java",
"lineNumber": 190,
"nativeMethod": false,
"className": "org.springframework.web.method.support.InvocableHandlerMethod"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invokeForRequest",
"fileName": "InvocableHandlerMethod.java",
"lineNumber": 138,
"nativeMethod": false,
"className": "org.springframework.web.method.support.InvocableHandlerMethod"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invokeAndHandle",
"fileName": "ServletInvocableHandlerMethod.java",
"lineNumber": 105,
"nativeMethod": false,
"className": "org.springframework.web.servlet.mvc.method.annotation.ServletInvocableHandlerMethod"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invokeHandlerMethod",
"fileName": "RequestMappingHandlerAdapter.java",
"lineNumber": 879,
"nativeMethod": false,
"className": "org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "handleInternal",
"fileName": "RequestMappingHandlerAdapter.java",
"lineNumber": 793,
"nativeMethod": false,
"className": "org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "handle",
"fileName": "AbstractHandlerMethodAdapter.java",
"lineNumber": 87,
"nativeMethod": false,
"className": "org.springframework.web.servlet.mvc.method.AbstractHandlerMethodAdapter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doDispatch",
"fileName": "DispatcherServlet.java",
"lineNumber": 1040,
"nativeMethod": false,
"className": "org.springframework.web.servlet.DispatcherServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doService",
"fileName": "DispatcherServlet.java",
"lineNumber": 943,
"nativeMethod": false,
"className": "org.springframework.web.servlet.DispatcherServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "processRequest",
"fileName": "FrameworkServlet.java",
"lineNumber": 1006,
"nativeMethod": false,
"className": "org.springframework.web.servlet.FrameworkServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doGet",
"fileName": "FrameworkServlet.java",
"lineNumber": 898,
"nativeMethod": false,
"className": "org.springframework.web.servlet.FrameworkServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "service",
"fileName": "HttpServlet.java",
"lineNumber": 634,
"nativeMethod": false,
"className": "javax.servlet.http.HttpServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "service",
"fileName": "FrameworkServlet.java",
"lineNumber": 883,
"nativeMethod": false,
"className": "org.springframework.web.servlet.FrameworkServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "service",
"fileName": "HttpServlet.java",
"lineNumber": 741,
"nativeMethod": false,
"className": "javax.servlet.http.HttpServlet"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 231,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "WsFilter.java",
"lineNumber": 53,
"nativeMethod": false,
"className": "org.apache.tomcat.websocket.server.WsFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": null,
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "CorsFilter.java",
"lineNumber": 27,
"nativeMethod": false,
"className": "com.eunobox.eunoboxbackend.filter.CorsFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 320,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "FilterSecurityInterceptor.java",
"lineNumber": 126,
"nativeMethod": false,
"className": "org.springframework.security.web.access.intercept.FilterSecurityInterceptor"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterSecurityInterceptor.java",
"lineNumber": 90,
"nativeMethod": false,
"className": "org.springframework.security.web.access.intercept.FilterSecurityInterceptor"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ExceptionTranslationFilter.java",
"lineNumber": 118,
"nativeMethod": false,
"className": "org.springframework.security.web.access.ExceptionTranslationFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "SessionManagementFilter.java",
"lineNumber": 137,
"nativeMethod": false,
"className": "org.springframework.security.web.session.SessionManagementFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "AnonymousAuthenticationFilter.java",
"lineNumber": 111,
"nativeMethod": false,
"className": "org.springframework.security.web.authentication.AnonymousAuthenticationFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "SecurityContextHolderAwareRequestFilter.java",
"lineNumber": 158,
"nativeMethod": false,
"className": "org.springframework.security.web.servletapi.SecurityContextHolderAwareRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "RequestCacheAwareFilter.java",
"lineNumber": 63,
"nativeMethod": false,
"className": "org.springframework.security.web.savedrequest.RequestCacheAwareFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OAuth2AuthenticationProcessingFilter.java",
"lineNumber": 176,
"nativeMethod": false,
"className": "org.springframework.security.oauth2.provider.authentication.OAuth2AuthenticationProcessingFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "LogoutFilter.java",
"lineNumber": 116,
"nativeMethod": false,
"className": "org.springframework.security.web.authentication.logout.LogoutFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doHeadersAfter",
"fileName": "HeaderWriterFilter.java",
"lineNumber": 92,
"nativeMethod": false,
"className": "org.springframework.security.web.header.HeaderWriterFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "HeaderWriterFilter.java",
"lineNumber": 77,
"nativeMethod": false,
"className": "org.springframework.security.web.header.HeaderWriterFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OncePerRequestFilter.java",
"lineNumber": 119,
"nativeMethod": false,
"className": "org.springframework.web.filter.OncePerRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "SecurityContextPersistenceFilter.java",
"lineNumber": 105,
"nativeMethod": false,
"className": "org.springframework.security.web.context.SecurityContextPersistenceFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "WebAsyncManagerIntegrationFilter.java",
"lineNumber": 56,
"nativeMethod": false,
"className": "org.springframework.security.web.context.request.async.WebAsyncManagerIntegrationFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OncePerRequestFilter.java",
"lineNumber": 119,
"nativeMethod": false,
"className": "org.springframework.web.filter.OncePerRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 334,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy$VirtualFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "FilterChainProxy.java",
"lineNumber": 215,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "FilterChainProxy.java",
"lineNumber": 178,
"nativeMethod": false,
"className": "org.springframework.security.web.FilterChainProxy"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invokeDelegate",
"fileName": "DelegatingFilterProxy.java",
"lineNumber": 358,
"nativeMethod": false,
"className": "org.springframework.web.filter.DelegatingFilterProxy"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "DelegatingFilterProxy.java",
"lineNumber": 271,
"nativeMethod": false,
"className": "org.springframework.web.filter.DelegatingFilterProxy"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "RequestContextFilter.java",
"lineNumber": 100,
"nativeMethod": false,
"className": "org.springframework.web.filter.RequestContextFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OncePerRequestFilter.java",
"lineNumber": 119,
"nativeMethod": false,
"className": "org.springframework.web.filter.OncePerRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "FormContentFilter.java",
"lineNumber": 93,
"nativeMethod": false,
"className": "org.springframework.web.filter.FormContentFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OncePerRequestFilter.java",
"lineNumber": 119,
"nativeMethod": false,
"className": "org.springframework.web.filter.OncePerRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "WebMvcMetricsFilter.java",
"lineNumber": 93,
"nativeMethod": false,
"className": "org.springframework.boot.actuate.metrics.web.servlet.WebMvcMetricsFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OncePerRequestFilter.java",
"lineNumber": 119,
"nativeMethod": false,
"className": "org.springframework.web.filter.OncePerRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilterInternal",
"fileName": "CharacterEncodingFilter.java",
"lineNumber": 201,
"nativeMethod": false,
"className": "org.springframework.web.filter.CharacterEncodingFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "OncePerRequestFilter.java",
"lineNumber": 119,
"nativeMethod": false,
"className": "org.springframework.web.filter.OncePerRequestFilter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "internalDoFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 193,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doFilter",
"fileName": "ApplicationFilterChain.java",
"lineNumber": 166,
"nativeMethod": false,
"className": "org.apache.catalina.core.ApplicationFilterChain"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "StandardWrapperValve.java",
"lineNumber": 202,
"nativeMethod": false,
"className": "org.apache.catalina.core.StandardWrapperValve"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "StandardContextValve.java",
"lineNumber": 96,
"nativeMethod": false,
"className": "org.apache.catalina.core.StandardContextValve"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "AuthenticatorBase.java",
"lineNumber": 541,
"nativeMethod": false,
"className": "org.apache.catalina.authenticator.AuthenticatorBase"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "StandardHostValve.java",
"lineNumber": 139,
"nativeMethod": false,
"className": "org.apache.catalina.core.StandardHostValve"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "ErrorReportValve.java",
"lineNumber": 92,
"nativeMethod": false,
"className": "org.apache.catalina.valves.ErrorReportValve"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "invoke",
"fileName": "StandardEngineValve.java",
"lineNumber": 74,
"nativeMethod": false,
"className": "org.apache.catalina.core.StandardEngineValve"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "service",
"fileName": "CoyoteAdapter.java",
"lineNumber": 343,
"nativeMethod": false,
"className": "org.apache.catalina.connector.CoyoteAdapter"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "service",
"fileName": "Http11Processor.java",
"lineNumber": 373,
"nativeMethod": false,
"className": "org.apache.coyote.http11.Http11Processor"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "process",
"fileName": "AbstractProcessorLight.java",
"lineNumber": 65,
"nativeMethod": false,
"className": "org.apache.coyote.AbstractProcessorLight"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "process",
"fileName": "AbstractProtocol.java",
"lineNumber": 868,
"nativeMethod": false,
"className": "org.apache.coyote.AbstractProtocol$ConnectionHandler"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "doRun",
"fileName": "NioEndpoint.java",
"lineNumber": 1590,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.NioEndpoint$SocketProcessor"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "SocketProcessorBase.java",
"lineNumber": 49,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.SocketProcessorBase"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1136,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [
{
"className": "org.apache.tomcat.util.net.NioEndpoint$NioSocketWrapper",
"identityHashCode": 266775302,
"lockedStackDepth": 97,
"lockedStackFrame": {
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "SocketProcessorBase.java",
"lineNumber": 49,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.SocketProcessorBase"
}
}
],
"lockedSynchronizers": [
{
"className": "java.util.concurrent.ThreadPoolExecutor$Worker",
"identityHashCode": 1896442895
}
],
"lockInfo": null
},
{
"threadName": "http-nio-8080-exec-6",
"threadId": 1840,
"blockedTime": -1,
"blockedCount": 1,
"waitedTime": -1,
"waitedCount": 17,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-7",
"threadId": 1841,
"blockedTime": -1,
"blockedCount": 3,
"waitedTime": -1,
"waitedCount": 19,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-8",
"threadId": 1842,
"blockedTime": -1,
"blockedCount": 1,
"waitedTime": -1,
"waitedCount": 17,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-9",
"threadId": 1843,
"blockedTime": -1,
"blockedCount": 1,
"waitedTime": -1,
"waitedCount": 18,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-exec-10",
"threadId": 1844,
"blockedTime": -1,
"blockedCount": 1,
"waitedTime": -1,
"waitedCount": 18,
"lockName": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject@571cf703",
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": false,
"suspended": false,
"threadState": "WAITING",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "Unsafe.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "jdk.internal.misc.Unsafe"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "park",
"fileName": "LockSupport.java",
"lineNumber": 341,
"nativeMethod": false,
"className": "java.util.concurrent.locks.LockSupport"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "block",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 506,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionNode"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "unmanagedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3463,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "managedBlock",
"fileName": "ForkJoinPool.java",
"lineNumber": 3434,
"nativeMethod": false,
"className": "java.util.concurrent.ForkJoinPool"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "await",
"fileName": "AbstractQueuedSynchronizer.java",
"lineNumber": 1623,
"nativeMethod": false,
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "take",
"fileName": "LinkedBlockingQueue.java",
"lineNumber": 435,
"nativeMethod": false,
"className": "java.util.concurrent.LinkedBlockingQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 107,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "take",
"fileName": "TaskQueue.java",
"lineNumber": 33,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskQueue"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "getTask",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1062,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "runWorker",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 1122,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "ThreadPoolExecutor.java",
"lineNumber": 635,
"nativeMethod": false,
"className": "java.util.concurrent.ThreadPoolExecutor$Worker"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "TaskThread.java",
"lineNumber": 61,
"nativeMethod": false,
"className": "org.apache.tomcat.util.threads.TaskThread$WrappingRunnable"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [],
"lockInfo": {
"className": "java.util.concurrent.locks.AbstractQueuedSynchronizer$ConditionObject",
"identityHashCode": 1461516035
}
},
{
"threadName": "http-nio-8080-ClientPoller",
"threadId": 1845,
"blockedTime": -1,
"blockedCount": 3,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": true,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "wait",
"fileName": "WEPoll.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.nio.ch.WEPoll"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "doSelect",
"fileName": "WEPollSelectorImpl.java",
"lineNumber": 111,
"nativeMethod": false,
"className": "sun.nio.ch.WEPollSelectorImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "lockAndDoSelect",
"fileName": "SelectorImpl.java",
"lineNumber": 129,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "select",
"fileName": "SelectorImpl.java",
"lineNumber": 141,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "NioEndpoint.java",
"lineNumber": 709,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.NioEndpoint$Poller"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [
{
"className": "sun.nio.ch.Util$2",
"identityHashCode": 399821743,
"lockedStackDepth": 2,
"lockedStackFrame": {
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "lockAndDoSelect",
"fileName": "SelectorImpl.java",
"lineNumber": 129,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
}
},
{
"className": "sun.nio.ch.WEPollSelectorImpl",
"identityHashCode": 1996632628,
"lockedStackDepth": 2,
"lockedStackFrame": {
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "lockAndDoSelect",
"fileName": "SelectorImpl.java",
"lineNumber": 129,
"nativeMethod": false,
"className": "sun.nio.ch.SelectorImpl"
}
}
],
"lockedSynchronizers": [],
"lockInfo": null
},
{
"threadName": "http-nio-8080-Acceptor",
"threadId": 1846,
"blockedTime": -1,
"blockedCount": 0,
"waitedTime": -1,
"waitedCount": 0,
"lockName": null,
"lockOwnerId": -1,
"lockOwnerName": null,
"daemon": true,
"inNative": true,
"suspended": false,
"threadState": "RUNNABLE",
"priority": 5,
"stackTrace": [
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "Net.java",
"lineNumber": -2,
"nativeMethod": true,
"className": "sun.nio.ch.Net"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "implAccept",
"fileName": "ServerSocketChannelImpl.java",
"lineNumber": 425,
"nativeMethod": false,
"className": "sun.nio.ch.ServerSocketChannelImpl"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "accept",
"fileName": "ServerSocketChannelImpl.java",
"lineNumber": 391,
"nativeMethod": false,
"className": "sun.nio.ch.ServerSocketChannelImpl"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "serverSocketAccept",
"fileName": "NioEndpoint.java",
"lineNumber": 469,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.NioEndpoint"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "serverSocketAccept",
"fileName": "NioEndpoint.java",
"lineNumber": 71,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.NioEndpoint"
},
{
"classLoaderName": "app",
"moduleName": null,
"moduleVersion": null,
"methodName": "run",
"fileName": "Acceptor.java",
"lineNumber": 95,
"nativeMethod": false,
"className": "org.apache.tomcat.util.net.Acceptor"
},
{
"classLoaderName": null,
"moduleName": "java.base",
"moduleVersion": "17.0.4.1",
"methodName": "run",
"fileName": "Thread.java",
"lineNumber": 833,
"nativeMethod": false,
"className": "java.lang.Thread"
}
],
"lockedMonitors": [],
"lockedSynchronizers": [
{
"className": "java.util.concurrent.locks.ReentrantLock$NonfairSync",
"identityHashCode": 1621120158
}
],
"lockInfo": null
}
]
}
```
