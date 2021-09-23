# BankSim


title BankSim

thread mainThread
space 
activate mainThread

mainThread->>*thread1:<<create>>
mainThread->>thread1:start
activate thread1

mainThread->>*thread2:<<create>>
mainThread->>thread2:start
activate thread2

mainThread->>*thread3:<<create>>
mainThread->>thread3:start
activate thread3

mainThread->>*thread4:<<create>>
mainThread->>thread4:start
activate thread4

mainThread->>*thread5:<<create>>
mainThread->>thread5:start
activate thread5

mainThread->>*thread6:<<create>>
mainThread->>thread6:start
activate thread6

mainThread->>*thread7:<<create>>
mainThread->>thread7:start
activate thread7

mainThread->>*thread8:<<create>>
mainThread->>thread8:start
activate thread8

mainThread->>*thread9:<<create>>
mainThread->>thread9:start
activate thread9

