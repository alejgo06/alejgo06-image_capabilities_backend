# image capabilities service

This api receives an image and a json with some coordinates return some capabilities. 

Each version is independent each other
# versions:

- V1. {color}
- V2. {count}
- V3. {shape}
- V4. {classify background}
- V5. {detect positions, near, close}

# run 

uvicorn backend:app --reload --port 8021

http://127.0.0.1:8021/docs#/default