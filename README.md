# Z_Crypto_Trader

I have created a C++ crypto trading application which I use to profitable trade
automatedly 24/7.  The low latency application trades on multiple exchanges.  Also, the program is a 
thread-safe multi-threaded application with sub millisecond latency utilizing thread-safe queues for lock free 
inter-thread communications.  GTK was used to develop the GUI and debugging was aided by
gdb, gprof and valgrid.  Asynchronous programming was utilized to deal with networking lags.
