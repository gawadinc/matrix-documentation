## Community
Please visit our community support forums at:
[community.matrix.one](http://community.matrix.one/)

## Check Active MATRIX CORE Services

Run the following command on your Raspberry Pi's terminal to see the MATRIX Services currently running.
```language-bash
ps aux | grep 'malos'
```

## Audio Open Error
If you encounter the error log below, your microphones are being used by the Pocketsphinx service for the [Wakeword Driver](protocols/wakeword).
```
arecord: main:788: audio open error: Device or resource busy
```
You can solve this by running the following command to kill the service.
```language-bash
sudo pkill malos_wakeword
```

<!-- ### Running Services Manually

If your services are not listed as shown above, you can run them manually using the following terminal commands:

```
# Running MATRIX CORE Sensors & Comm. Services
$ malos

# Running MATRIX CORE Vision Services
$ malos_eye
```

### Stopping Services

```
# Stopping the services altogether

$ pkill -9 malos
$ pkill -9 malos_eye
``` -->