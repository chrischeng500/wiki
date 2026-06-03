# BGP

## Path Selection
BGP uses a well-known decision process (Weight → LOCAL_PREF → ...).

!!! tip "Quick Reference"
    Always set `next-hop-self` on iBGP peers.

```python
# Example: Paramiko-based BGP neighbor check
import paramiko
...
```