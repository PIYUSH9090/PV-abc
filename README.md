# PV and PVC connection

First we will create pvc then we will get pv and pvc both.
After then we need to get the yaml file of that automatically created pv with this command

```
kubectl pv << pv name >> -o yaml
```

So now we will get yaml of that pv.

Now as a referemce we need to see that yaml file and make another pv2.yaml for another pvc2.yaml, which both are connected each other.

pvc2 should be bound on pv2.

This is what we want ... :)