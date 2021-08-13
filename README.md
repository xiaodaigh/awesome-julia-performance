# awesome-julia-performance

## Main list
Packages and other resourced designed to make things run fast in Julia #julialang

| Package | Comment |
| ------- | ------- |
| [ThreadPools.jl](https://github.com/tro3/ThreadPools.jl) | Background threads and queued threads  |
| [LoopVectorization.jl](https://github.com/JuliaSIMD/LoopVectorization.jl) | `@turbo` macro for speedier loops/iterations backed by AVX  |
| [FLoops.jl](https://github.com/JuliaFolds/FLoops.jl) | `fold` for humans  |
| [Tullio.jl](https://github.com/mcabbott/Tullio.jl) | Einstein notation backed by AVX, I think. Not 100% sure  |
| [Catwalk.jl](github.com/tisztamo/Catwalk.jl/) | Speeds up dynamic dispatch for workloads where the one function `fn` can be dispatch on many things e.g. within a loop |
| [PreallocationTools.jl](https://github.com/SciML/PreallocationTools.jl) | Make functions that re-use pre-allocated memory |
 

## Other resources
| Resource | Comment |
| ------- | ------- |
| https://symbolics.juliasymbolics.org/dev/tutorials/auto_parallel/ | Tutorial: improve codegen tool | 
| [AutoPreallocation.jl](https://github.com/oxinabox/AutoPreallocation.jl) |  Similar to PreallocationTools.jl. "fun but more of an experiment" |
 
