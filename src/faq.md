# FAQ

## My node is running but is not visible by peers

Check that you opened the 35555 port in your firewall settings and the node listens to it:

```
sudo netstat -tulpn
```

## I receive {"code":32003,"message":"state query failed: ValueNotFound(\"Failed to find base key at path: Key::Account(...)\")"} when checking the balance

Make sure that you are using the hex representation of the correct public key, and that the key is funded.

## I do not see my bid in the auction info

Check the transaction status to ensure it went through:

[include casper-client/check-transaction-status.md]

## I do not see my bid in the auction info

Check the transaction status to ensure it went through:

[include casper-client/check-transaction-status.md]