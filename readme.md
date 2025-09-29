# Gogrant

Interactive CLI that writes a Vagrantfile for a VirtualBox VM.

Requires Go 1.25 or later, Vagrant, and VirtualBox.

```sh
go run .
```

Answer the prompts to configure the box, hostname, memory, CPU count, and
network interfaces. The resulting `Vagrantfile` is written to the current
directory.
