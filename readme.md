# Cookie based auth template

## Steps to use it 🐇

> backend
 
- `cd backend\\`: install the npm packages using `npm i` (presuming your current bundler is npm :D)

- compile ts code into js using `npm run build`
- initiate the server by `npm run start`
- send api requests using POSTMAN and check headers from server side, look for **set-cookie** 
   - Also: cookies are cached, so you can revisit them in the cookies section (since postman mimics as a browser).
  
---

> frontend
- install packages: `npm i`
- initiate the dev server: `npm run dev`
- hit '/signin' route on the dev server. 

---
## Postman Screenshots 🚀

### app.post('/signin', ...)
![alt text](image.png)

### app.get('/user', ...)
![alt text](image-2.png)


### cached cookies
![alt text](image-1.png)