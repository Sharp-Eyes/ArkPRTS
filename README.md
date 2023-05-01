# ArkPRTS

Arknights python wrapper.

---

Source Code: <https://github.com/thesadru/arkprts>

---

## Usage

```py
import arkprts

async def main() -> None:
    client = arkprts.Client()
    await client.login_with_email("user@gmail.com")
    # or client.login_with_token("123456", "abcdefg")

    data = await client.get_data()
    print("Level: ", data["user"]["status"]["level"])
```

There are unfortunately no models due to the sheer size of the returned data.

## Contributing

Any kind of contribution is welcome.
Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for more information.