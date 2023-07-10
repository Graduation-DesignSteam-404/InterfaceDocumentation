# InterfaceDocumentation

接口文档



### 此文档由[https://apifox.com/](Apifox)生成



# jian

exported at 2023-07-10 15:14:24

## fixupUser

fixupUser

---

### fixupUser

> BASIC

**Path:** fixupUser

**Method:** POST

> REQUEST

**Query:**

| name    | value | required | desc |
| ------- | ----- | -------- | ---- |
| newName |       | YES      |      |
| oldName |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**

## appendUser

appendUser

---

### appendUser

> BASIC

**Path:** appendUser

**Method:** POST

> REQUEST

**Query:**

| name | value | required | desc |
| ---- | ----- | -------- | ---- |
| name |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**

## allUser

allUser

---

### allUser

> BASIC

**Path:** allUser

**Method:** GET

> REQUEST

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type   | desc |
| ---- | ------ | ---- |
|      | array  |      |
|      | object |      |

**Response Demo:**

```json
[
  {}
]
```

## borrowing

borrowing

---

### borrowing

> BASIC

**Path:** borrowing

**Method:** POST

> REQUEST

**Query:**

| name | value | required | desc |
| ---- | ----- | -------- | ---- |
| book |       | YES      |      |
| user |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**

```json
1
    success   
-1 
    book absent
-2 
    user absent
```

## allUserName

allUserName

---

### allUserName

> BASIC

**Path:** allUserName

**Method:** GET

> REQUEST

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type   | desc |
| ---- | ------ | ---- |
|      | array  |      |
|      | object |      |

**Response Demo:**

```json
[
  {}
]
```

## allBookName

allBookName

---

### allBookName

> BASIC

**Path:** allBookName

**Method:** GET

> REQUEST

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type   | desc |
| ---- | ------ | ---- |
|      | array  |      |
|      | object |      |

**Response Demo:**

```json
[
  {}
]
```

## removeBook

removeBook

---

### removeBook

> BASIC

**Path:** removeBook

**Method:** POST

> REQUEST

**Query:**

| name | value | required | desc |
| ---- | ----- | -------- | ---- |
| name |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**

## returnBook

returnBook

---

### returnBook

> BASIC

**Path:** returnBook

**Method:** POST

> REQUEST

**Query:**

| name | value | required | desc |
| ---- | ----- | -------- | ---- |
| book |       | YES      |      |
| user |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**

## appendBook

appendBook

---

### appendBook

> BASIC

**Path:** appendBook

**Method:** POST

> REQUEST

**Query:**

| name   | value | required | desc |
| ------ | ----- | -------- | ---- |
| name   |       | YES      |      |
| author |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**

## allBook

allBook

---

### allBook

> BASIC

**Path:** allBook

**Method:** GET

> REQUEST

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type   | desc |
| ---- | ------ | ---- |
|      | array  |      |
|      | object |      |

**Response Demo:**

```json
[
  {}
]
```

## removeUser

removeUser

---

### removeUser

> BASIC

**Path:** removeUser

**Method:** POST

> REQUEST

**Query:**

| name | value | required | desc |
| ---- | ----- | -------- | ---- |
| name |       | YES      |      |

> RESPONSE

**Headers:**

| name         | value                          | required | desc |
| ------------ | ------------------------------ | -------- | ---- |
| content-type | application/json;charset=UTF-8 | NO       |      |

**Body:**

| name | type    | desc |
| ---- | ------- | ---- |
|      | integer |      |

**Response Demo:**
