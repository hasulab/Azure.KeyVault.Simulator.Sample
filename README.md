# Azure.KeyVault.Simulator.Sample
Azure KeyVault Simulator Sample
## Getting Started 

* Create a new ASP.NET  Code empty Project
* Add latest Hasulab.Azure.KeyVault.Simulator library reference from nuget.org
* Add following lines to Progarm.cs
```
builder.Services.AddLogging();
builder.Services.AddKeyVaultSimulatorServices(builder.Configuration);

//Other codes
app.MapKeyVaultSimulatorEndpoint();

```
