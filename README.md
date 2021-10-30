# Problems Hodgepodge

* NVIDIA Cuda Driver Installation under Linux

> [INFO]: Finished with code: 256
> [ERROR]: Install of driver component failed.

Solution: Close `lightdm`, then install.

```
sudo /etc/init.d/lightdm stop
```

