# thundering_herd
 epoll惊群问题（thundering_herd ）自从Linux2.6内核开始实现epoll就已存在，实际到Linux内核4.5.x Linus修复了此 [issue](https://github.com/torvalds/linux/commit/df0108c5da561c66c333bb46bfe3c1fc65905898#diff-9bfb06d2fc75db840dd2e93bb9759c05f2b368ff8d97c84d642a8d1e39d4b000).
所以该案例只有在Linux 4.5.x 内核之前才会看到惊群效果。
