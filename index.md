# creating Headers using markdown
  ## \_Think am getting the hang off it \_
 \_Think am getting the hang off it \_
 
- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete

hello _world_.
```javascript
function startWebcam() {
  navigator.mediaDevices
    .getUserMedia({
      video: true,
      audio: false,
    })
    .then((stream) => {
      video.srcObject = stream;
    })
    .catch((error) => {
      console.error(error);
    });
}


´´´

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
