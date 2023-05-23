<div align="center">
    <img src="https://buildjet.com/buildjet-for-github-actions-logo2.svg" height="38">
</div>

---

This is a fork by [BuildJet for GitHub Actions](https://buildjet.com/for-github-actions).
It is **fully compatible with the official setup-dotnet action**, simply replace `actions/setup-dotnet` with `buildjet/setup-dotnet`. 
Under the hood we simply switch the underlying caching package to our fully compatible `buildjet/cache`. No other changes have been made to this package.

For help migrating to BuildJet's setup-dotnet, please visit our [migration guide](https://buildjet.com/for-github-actions/docs/guides/migrating-to-buildjet-cache).  
For detailed usage instructions, please visit the [official `actions/setup-dotnet` repository](https://github.com/actions/setup-dotnet).
