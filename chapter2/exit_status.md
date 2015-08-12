## Exit Status Codes

In our example we used an exit status code of MIQ_OK. Although with simple methods such as this we don't strictly need to specify an exit code, it's good practice to do so. When we build more advanced multi-Method Classes and State Machines, an exit code can signal an error condition to the Automation Engine so that action can be taken.

There are four exit codes that we can use:

**MIQ\_OK** (0) - Continues normal processing


```
```

This is logged to automation.log as:

```
Method exited with rc=MIQ_WARN
```


```
```


```
```