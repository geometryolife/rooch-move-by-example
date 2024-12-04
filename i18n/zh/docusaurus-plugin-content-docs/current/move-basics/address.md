# Address

Address is a unique identifier of a location on the blockchain. It is used to identify
[packages](./packages.md), [accounts](./what-is-an-account.md), and [objects](./object-storage.md).
Address has a fixed size of 32 bytes and is usually represented as a hexadecimal string prefixed
with `0x`. Addresses are case insensitive.

```move
0xe51ff5cd221a81c3d6e22b9e670ddf99004d71de4f769b0312b68c7c4872e2f1
```

The address above is an example of a valid address. It is 64 characters long (32 bytes) and prefixed
with `0x`.

Rooch also has reserved addresses that are used to identify standard packages and objects. Reserved
addresses are typically simple values that are easy to remember and type. For example, the address
of the Standard Library is `0x1`. Addresses, shorter than 32 bytes, are padded with zeros to the
left.

```move
0x1 = 0x0000000000000000000000000000000000000000000000000000000000000001
```

Here are some examples of reserved addresses:

- `0x1` - address of the Move Standard Library (alias `std`)
- `0x2` - address of the MoveOS Standard Library (alias `moveos_std`)
- `0x3` - address of the Rooch Framework (alias `rooch_framework`)

