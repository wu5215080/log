# log
go log


 log with different level
 log.Info("hello world")
 log.Error("hello world")

 //create a logger with specified handler
 h := NewStreamHandler(os.Stdout)
 l := log.NewDefault(h)
 l.Info("hello world")
 l.Infof("%s %d", "hello", 123)
