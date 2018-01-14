# HasGoogleStreetView
Check if GPS coordinates has google street view

# Installation 
```bash
curl -sSLf https://raw.githubusercontent.com/assafmo/HasGoogleStreetView/master/has_street_view.sh | sudo tee /usr/local/bin/has_street_view > /dev/null
sudo chmod +x /usr/local/bin/has_street_view
```

# Usage
```bash
$ has_street_view 32.0852118 35.7819609
false
$ echo $?
0
```
```bash
$ has_street_view 32.070145 34.7897973
true
$ echo $?
0
```
