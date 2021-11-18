# crank-usage
https://github.com/dotnet/crank
https://github.com/aspnet/benchmarks
https://www.youtube.com/watch?v=2IgfrnG-128&t=411s&ab_channel=dotNET
## install crank using powershell
dotnet tool update Microsoft.Crank.Controller --version "0.2.0-*" --global

## install crank agent
dotnet tool update Microsoft.Crank.Agent --version "0.2.0-*" --global

## run agent in powershell
crank-agent


## run crank from project folder
crank --config .\benchmark.benchmarks.yml --scenario hello --profile local

## run against net6.0 framework
crank --config .\benchmark.benchmarks.yml --scenario hello --profile local --application.framework net6.0



