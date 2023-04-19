# dostep
dostep
```
dostep<-function(x,y){
  n<-length(x)
  xrep<-rep(x,c(1,rep(2,n-1)))
  yrep<-rep(y,c(rep(2,n-1),1))
  result<-list(x=xrep,y=yrep)
  return(result)
}
```
