# Custom Contexts

This an example that shows how to create or defined a custom contexts for VitalPBX. For this example we have created an extension to retrieve and say the current external IP address of the server using [ipinfo.io](https://ipinfo.io/) service.

[Full Tutorial](https://www.vitalpbx.org/blog/customizing-vitalpbxs-dial-plan/)

## Installing

```
yum install wget -y
wget https://raw.githubusercontent.com/VitalPBX/custom-contexts/master/cc-install.sh
chmod +x cc-install.sh
./cc-install.sh
```

Once you have installed the custom context script, you will be able to dial **7747**, and hear your server public IP address.
