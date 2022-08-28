# P-Arch Project
Well this is a pretty simple project, It helps you make VB.NET apps but with an already generated api that you can make code on, so far there's a bunch of keys like darkmode, log, circle, circlex, circley and username, the way to access it is using this code-
  Dim reader = My.Computer.FileSystem.ReadAllText("<apikey>")
that's how easy it is.. to write into it you can use-
  Dim writer = My.Computer.FileSystem.WriteAllText("<apikey>", "<value>", False)
 the last argument false is your choice but false is preferred.
 Well that's it!
