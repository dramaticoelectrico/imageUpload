## Cloudinary API image upload

Nodejs
Upload with responsive image sizes

# Data Structure:
```javascript
{
  "success": true,
  "message": "file uploaded",
  "data": {
    "public_id": "2020-01-23T01:55:56.602Z",
    "version": 1579744560,
    "signature": "",
    "width": 640,
    "height": 480,
    "format": "jpg",
    "resource_type": "image",
    "created_at": "2020-01-23T01:56:00Z",
    "tags": [],
    "bytes": 284237,
    "type": "upload",
    "etag": "",
    "placeholder": false,
    "url": "http://res.cloudinary.com/{{name}}/image/upload/v1579744560/2020-01-23T01:55:56.602Z.jpg",
    "secure_url": "https://res.cloudinary.com/{{name}}/image/upload/v1579744560/2020-01-23T01:55:56.602Z.jpg",
    "original_filename": "tmp-1-1579744556595",
    "responsive_breakpoints": [
      {
        "breakpoints": [
          {
            "width": 640,
            "height": 480,
            "bytes": 70337,
            "url": "http://res.cloudinary.com/{{name}}/image/upload/c_scale,w_640/v1579744560/2020-01-23T01:55:56.602Z.jpg",
            "secure_url": "https://res.cloudinary.com/{{name}}/image/upload/c_scale,w_640/v1579744560/2020-01-23T01:55:56.602Z.jpg"
          },
          {
            "width": 547,
            "height": 410,
            "bytes": 49354,
            "url": "http://res.cloudinary.com/{{name}}/image/upload/c_scale,w_547/v1579744560/2020-01-23T01:55:56.602Z.jpg",
            "secure_url": "https://res.cloudinary.com/{{name}}/image/upload/c_scale,w_547/v1579744560/2020-01-23T01:55:56.602Z.jpg"
          },
          {
            "width": 387,
            "height": 290,
            "bytes": 27801,
            "url": "http://res.cloudinary.com/{{name}}/image/upload/c_scale,w_387/v1579744560/2020-01-23T01:55:56.602Z.jpg",
            "secure_url": "https://res.cloudinary.com/{{name}}/image/upload/c_scale,w_387/v1579744560/2020-01-23T01:55:56.602Z.jpg"
          },
          {
            "width": 200,
            "height": 150,
            "bytes": 8849,
            "url": "http://res.cloudinary.com/{{name}}/image/upload/c_scale,w_200/v1579744560/2020-01-23T01:55:56.602Z.jpg",
            "secure_url": "https://res.cloudinary.com/{{name}}/image/upload/c_scale,w_200/v1579744560/2020-01-23T01:55:56.602Z.jpg"
          }
        ]
      }
    ]
  }
}
```
