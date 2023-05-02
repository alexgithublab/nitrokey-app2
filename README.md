# Nitrokey App 2

This application allows to manage Nitrokey 3 devices. Currently, it only allows updating the firmware of Nitrokey 3 devices. More features will be added in the future. To manage Nitrokey Pro and Nitrokey Storage devices, use the older [Nitrokey App](https://github.com/Nitrokey/nitrokey-app).

## Download

Executable binaries for Linux and Windows as well as a MSI installer for Windows can be downloaded from the [releases](https://github.com/Nitrokey/nitrokey-app2/releases).

### Compiling for Linux and macOS

The application can be compiled by executing:

```
git clone https://github.com/Nitrokey/nitrokey-app2.git
cd nitrokey-app2
make update-venv
source venv/bin/activate
make build
nitrokeyapp
```

## Dependencies

* [pynitrokey ](https://github.com/Nitrokey/pynitrokey)
* Python >3.9

