# vercel.config

#### vercel.json

```
{
    "version" : 2,
    "name" : "Full Stack",
    "builds" : [
        {
            "src" : "./index.js",
            "use" : "@vercel/node"
        }
    ],
    "routes" : [
        {
            "src" : "/(.*)",
            "dest" : "/"
        }
    ]
}

```
