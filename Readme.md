#  Try .NET Enabled Samples
![dotnet try Enabled](https://img.shields.io/badge/Try_.NET-Enabled-501078.svg)

*Please read the [Try .NET quick setup guide](https://github.com/dotnet/try/blob/master/README.md) before starting the tutorial below.* 

<p align ="center">
<img src ="http://www.thepollyproject.org/content/images/2016/10/Polly-Logo@2x.png" width="250">
</p>
<h1 align ="center">Try .NET Samples of Polly, the .NET Resilience Framework</h1>

<h3 align ="center">Polly is a resilience framework for .NET, with it your applications will easily tolerate transient faults and longer outages in remote systems or infrastructure. With just a few lines of code your application will be far more robust and reliable.</h3>
<h3 align ="center">
These demos will walk through all the resilience policies offered by Polly.
</h3>

If you want to find out more, check the [Polly github page](https://github.com/App-vNext/Polly/), Bryan's [blog post on Polly](https://nodogmablog.bryanhogan.net/tag/polly/) or his [Pluralsight course](https://www.pluralsight.com/courses/polly-fault-tolerant-web-service-requests).

**About the author:** [Bryan Hogan](https://twitter.com/bryanjhogan) is a podcaster, blogger, speaker, loves writing software and helping others write software. 



### Table of Content 
- [Before you add Polly](lettingItFail.md)
- [Retrying when you get an exception](retryIfException.md)
- [Retrying when you get a bad result](retryIfIncorrectStatus.md)
- [Combining Result and Exception Based Retries](retryIfIncorrectStatusOrException.md)
- [Waiting Before Retrying](waitAndRetry.md)
- [Fallbacks 1](fallingBack.md)
- [Fallbacks 2](fallingBackAndReturningADefault.md)
- [Timeout](timeout.md)
- [Basic Circuit Breaker](basicCircuitBreaker.md)
- [Advanced Circuit Breaker](advancedCircuitBreaker.md)
- [Caching](caching.md)
- [Bulkhead Isolation](bulkheadIsolation.md)
- [Policy Wraps](wrap.md)
