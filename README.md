# high-performance-dotnet: Hiệu năng và tối ưu hóa hệ thống .NET

- Tổng quan về hiệu năng trong .NET
  - Tư duy đo lường – tối ưu
  - Tránh tối ưu hóa sớm
  - Hiểu về chi phí hệ thống

- Các công cụ đo hiệu năng
  - BenchmarkDotNet
  - dotTrace
  - PerfView
  - Visual Studio Profiler

- Các nguyên tắc tối ưu hóa
  - “Don’t guess, measure!”
  - Tradeoff CPU–memory–latency
  - Scale vs performance

- Cấu trúc bộ nhớ .NET
  - Stack vs Heap
  - Value vs Reference type
  - Layout trong memory

- Garbage Collector trong .NET
  - Generations
  - LOH
  - GC Modes
  - GC Tuning trong appsettings

- Tối ưu bộ nhớ ứng dụng
  - Giảm allocation
  - Span<T>
  - ArrayPool
  - Tránh boxing/unboxing

- Tối ưu hóa đa luồng và đồng thời
  - Task
  - async/await
  - ThreadPool
  - Parallel LINQ
  - Channels

- Tối ưu hóa hệ thống ASP.NET Core
  - Middleware
  - Response caching
  - Pooling
  - Connection reuse

- Tối ưu truy xuất dữ liệu và ORM
  - EF Core tracking vs no-tracking
  - Batching
  - Index
  - Lazy loading

- Tối ưu hệ thống microservices
  - REST vs gRPC
  - Distributed cache
  - Circuit breaker
  - Retry

- Cold start và khởi động ứng dụng .NET
  - IL Trimming
  - ReadyToRun
  - AOT
  - Pre-warming
  - Hosted Services

- Mẫu thiết kế hiệu năng cao trong .NET
  - CQRS
  - Pipeline pattern
  - Cache-aside
  - Actor model

