<img width="954" alt="image" src="https://user-images.githubusercontent.com/22546949/166138009-cd3bbda8-db9a-4a10-8ac8-d2c639cd12a2.png">


```
private static int fib(int N) {
  int[] dp = new int[N + 1];
  Arrays.fill(dp, 0);
  dp[0] = 0;
  dp[1] = 1;

  for (int i = 2; i <= N; i++) {
    dp[i] = dp[i - 1] + dp[i - 2];
  }

  return dp[N];
}
```
