# wintools


### Zip files with password
```
zip -re <file-name.zip> your-file-or-directory
```

### encode/decode file for base64
```
# encode
base64 -i <input-file> -o <output-file>

# decode
certutil -decode base64-file <origin-file>
```
