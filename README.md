# Ruby on Rails Performance Notes

This is my brain dump notes about Ruby on rails performance optimization.

## Memory issues

### Jemalloc

Jemalloc is use as alternative to default cruby memory allocator: `malloc`, it is claim to be more effective allocation for C, and it is compatible with MRI.

I have some experience taming Rails memory fragmentation in production, and one of how it was solved is with applying Jemalloc.

### Reference

- [Website](http://jemalloc.net/)
- [GitHub](https://github.com/jemalloc/jemalloc)
- [Menurunkan penggunaan memory untuk aplikasi Ruby (ID)](https://medium.com/binar-academy/menurunkan-penggunaan-memory-untuk-aplikasi-ruby-newbie-friendly-c7b2af11b4a8)
- [Lower memory usage of your rails app with jemalloc](https://bubblin.io/blog/jemalloc)
- [What causes Ruby memory bloat?](https://www.joyfulbikeshedding.com/blog/2019-03-14-what-causes-ruby-memory-bloat.html)


## References

- [Rails Guide - Performance Testing Rails Applications](https://guides.rubyonrails.org/v3.2/performance_testing.html)

## Books

### Ruby

- [Ruby Performance Optimization](https://pragprog.com/titles/adrpo/ruby-performance-optimization/)

### Rails

- [The complete guide to Rails performance](https://www.railsspeed.com/)
