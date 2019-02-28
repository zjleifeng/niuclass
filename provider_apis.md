<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [访问地址](#%E8%AE%BF%E9%97%AE%E5%9C%B0%E5%9D%80)
- [鉴权](#%E9%89%B4%E6%9D%83)
  - [参数](#%E5%8F%82%E6%95%B0)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B)
  - [返回](#%E8%BF%94%E5%9B%9E)
- [更新用户信息](#%E6%9B%B4%E6%96%B0%E7%94%A8%E6%88%B7%E4%BF%A1%E6%81%AF)
  - [参数](#%E5%8F%82%E6%95%B0-1)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-1)
  - [返回](#%E8%BF%94%E5%9B%9E-1)
  - [错误](#%E9%94%99%E8%AF%AF)
- [获取课程列表](#%E8%8E%B7%E5%8F%96%E8%AF%BE%E7%A8%8B%E5%88%97%E8%A1%A8)
  - [参数](#%E5%8F%82%E6%95%B0-2)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-2)
  - [返回](#%E8%BF%94%E5%9B%9E-2)
  - [错误](#%E9%94%99%E8%AF%AF-1)
- [创建机构](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84)
  - [参数](#%E5%8F%82%E6%95%B0-3)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-3)
  - [返回](#%E8%BF%94%E5%9B%9E-3)
  - [错误](#%E9%94%99%E8%AF%AF-2)
- [更新机构信息](#%E6%9B%B4%E6%96%B0%E6%9C%BA%E6%9E%84%E4%BF%A1%E6%81%AF)
  - [参数](#%E5%8F%82%E6%95%B0-4)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-4)
  - [返回](#%E8%BF%94%E5%9B%9E-4)
- [更新机构成员角色信息](#%E6%9B%B4%E6%96%B0%E6%9C%BA%E6%9E%84%E6%88%90%E5%91%98%E8%A7%92%E8%89%B2%E4%BF%A1%E6%81%AF)
  - [参数](#%E5%8F%82%E6%95%B0-5)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-5)
  - [返回](#%E8%BF%94%E5%9B%9E-5)
  - [错误](#%E9%94%99%E8%AF%AF-3)
- [创建课程](#%E5%88%9B%E5%BB%BA%E8%AF%BE%E7%A8%8B)
  - [参数](#%E5%8F%82%E6%95%B0-6)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-6)
  - [返回](#%E8%BF%94%E5%9B%9E-6)
- [更新课程信息](#%E6%9B%B4%E6%96%B0%E8%AF%BE%E7%A8%8B%E4%BF%A1%E6%81%AF)
  - [参数](#%E5%8F%82%E6%95%B0-7)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-7)
  - [返回](#%E8%BF%94%E5%9B%9E-7)
- [设置课程时间安排](#%E8%AE%BE%E7%BD%AE%E8%AF%BE%E7%A8%8B%E6%97%B6%E9%97%B4%E5%AE%89%E6%8E%92)
  - [参数](#%E5%8F%82%E6%95%B0-8)
    - [times 结构体](#times-%E7%BB%93%E6%9E%84%E4%BD%93)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-8)
  - [返回](#%E8%BF%94%E5%9B%9E-8)
- [设置课程成员](#%E8%AE%BE%E7%BD%AE%E8%AF%BE%E7%A8%8B%E6%88%90%E5%91%98)
  - [参数](#%E5%8F%82%E6%95%B0-9)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-9)
  - [返回](#%E8%BF%94%E5%9B%9E-9)
- [移除课程成员](#%E7%A7%BB%E9%99%A4%E8%AF%BE%E7%A8%8B%E6%88%90%E5%91%98)
  - [参数](#%E5%8F%82%E6%95%B0-10)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-10)
  - [返回](#%E8%BF%94%E5%9B%9E-10)
- [课程信息](#%E8%AF%BE%E7%A8%8B%E4%BF%A1%E6%81%AF)
  - [参数](#%E5%8F%82%E6%95%B0-11)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-11)
  - [返回](#%E8%BF%94%E5%9B%9E-11)
- [删除课程](#%E5%88%A0%E9%99%A4%E8%AF%BE%E7%A8%8B)
  - [参数](#%E5%8F%82%E6%95%B0-12)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-12)
  - [返回](#%E8%BF%94%E5%9B%9E-12)
- [创建机构用户](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)
  - [参数](#%E5%8F%82%E6%95%B0-13)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-13)
  - [返回](#%E8%BF%94%E5%9B%9E-13)
- [通过 MemberID 修改机构用户信息](#%E9%80%9A%E8%BF%87-memberid-%E4%BF%AE%E6%94%B9%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7%E4%BF%A1%E6%81%AF)
  - [参数](#%E5%8F%82%E6%95%B0-14)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-14)
- [移除机构用户](#%E7%A7%BB%E9%99%A4%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)
  - [参数](#%E5%8F%82%E6%95%B0-15)
    - [请求示例](#%E8%AF%B7%E6%B1%82%E7%A4%BA%E4%BE%8B-15)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 访问地址
- 线上： https://niuclass.qiniuapi.com
- 测试： https://api-niuclass.qiniu.io

## 鉴权
```
POST /login
```
### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`mobile`|`string`|是|渠道商在niuclass的账户|
|`password`|`string`|是|渠道商在niuclass账户的密码|

#### 请求示例
```json
POST /login
Content-Type: application/json

{
    "mobile": "192321213",
    "password": "Wxxhh2112333"
}
```
### 返回
返回的结果是 jwt token, 解析出来会有一个过期时间，如果过期了，那么渠道商需要重新鉴权。
在后面的每次请求都需要带上这个 jwt token，放在 header 里面里面：
`Authorization: Bearer {{token}}`
```json
{
    "token": "ebGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTgzLCJpc3N1cmVfYXQiOjE1NDgzMjQwsImV4cGlyZSI6NjI2MzIzfQ.cMyW1MNdF1HIk60p0XNgCWTh0mHX35G2ymaP4"
}
```


## 更新用户信息
```
PUT /api/user/profile
```
### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`user_id`|`string`|是|用户的唯一 ID|
|`name`|`string`|否|用户的昵称, 如果不传那么就不更新|
|`mobile`|`string`|否|用户的手机, 如果不传那么就不更新|
|`avatar`|`string`|否|用户的头像，需要完整的 可以访问的地址，如果不传那么就不更新|
|`email`|`string`|否|用户的邮箱，如果不传那么就不更新|
|`description`|`string`|否|用户简介，如果不传那么就不更新|

#### 请求示例
```json
PUT /api/user/profile
Content-Type: application/json
Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
{
    "user_id": "uuid",
    "name": "test1",
    "mobile": "1000000000",
    "avatar": "http://helloworld.png",
    "email": "test@qiniu.com",
    "description": "Hello world"
}
```
### 返回
```json
HTTP CODE 200
```
### 错误
- 400 参数错误
- 404 用户没有找到
- 500 服务内部错误

```json
HTTP CODE 500
{
    "message": "update userinfo failed",
    "code": "INTERNAL_SERVER_ERROR"
}

```

## 获取课程列表
```
GET /api/courses
```

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`limit`|`int`|否|每次请求的数据量，最大100，默认100|
|`offset`|`int`|否|偏移量，分页的时候需要|
|`start`|`timestamp`|否|时间范围，开始时间 单位 秒|
|`end`|`timestamp`|否|时间范围，结束时间 单位 秒，如果开始时间和结束时间都不传，默认返回在课程周期里面的课程|
|`organization_id`|否|机构ID，可以获取指定机构的课程，不传默认返回当前渠道商所以机构的课程|

#### 请求示例
```json
GET /api/courses?limit=50&offset=1
Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
### 返回
```json
HTTP CODE 200
{
    "items": [{
        "id": 23, // 课程 ID
        "title": "古诗词鉴赏", // 课程名称
        "poster_url": "https://hellwea.com/porst.png", // 课程封面
        "description": "古诗词鉴赏", // 课程描述
        "duration": 3600, // 单节课时长
        "latest_class_time": 1548381600, // 课程最近的开始时间
        "organization_id": 23 // 课程属于的组织ID
    }...]
}
```

### 错误
- 400 参数错误
- 500 服务内部错误
- 403 没有权限查看指定组织的课程
```json
http code 403
{
    "message": "can't access organization",
    "code": "FORBIDDEN"
}
```

## 创建机构
```
POST /api/organization
```

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`name`|`string`|是|机构名称|
|`organization_owner`|`string`|是|机构的owner ID|
|`slogan`|`string`|否|机构口号|
|`description`|`string`|否|机构描述|
|`logo`|`string`|否|机构logo|
|`company`|`string`|否|机构所属的公司|
|`max_podium_user`|`uint`|否|允许最大上台人数，默认为8，目前最大也为8|
|`max_clarity`|`string`|否|允许的最大清晰度，Normal: 标清 480P, SD: 高清 540P, HD: 超清 720P, FHD: 1080P。默认全部都可以选择|

#### 请求示例
```json
POST /api/organization
Content-Type: application/json
Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

{
    "name": "古诗词鉴赏",
    "organization_owner": "userid",
    "slogan": "It's easy to learn chinese poems",
    "description": "hello, welcome to our org",
    "logo": "https://helloworld.com/logo.png",
    "company": "未来科幻局"
}
```
### 返回
```json
HTTP CODE 201
{
    "id": 33,
    "name": "古诗词鉴赏",
    "slogan": "It's easy to learn chinese poems",
    "description": "hello, welcome to our org",
    "logo": "https://helloworld.com/logo.png",
    "company": "未来科幻局"
}
```
### 错误
- 400 参数错误
- 500 内部错误
```json
http code 500
{
    "message": "create organization failed",
    "code": "INTERNAL_SERVER_ERROR"
}
```

## 更新机构信息
```
PUT /api/organization/:id
```
- :id  是创建机构的时候返回的 `id`

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`name`|`string`|否|机构名称，如果不传就不更新|
|`slogan`|`string`|否|机构口号，如果不传就不更新|
|`description`|`string`|否|机构描述，如果不传就不更新|
|`logo`|`string`|否|机构logo，如果不传就不更新|
|`company`|`string`|否|机构所属的公司，如果不传就不更新|
|`max_podium_user`|`uint`|否|允许最大上台人数|
|`max_clarity`|`string`|否|允许的最大清晰度，Normal: 标清 480P, SD: 高清 540P, HD: 超清 720P, FHD: 1080P|

#### 请求示例
```json
PUT /api/organization/33
Content-Type: application/json
Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

{
    "name": "西方诗歌鉴赏",
    "slogan": "It's easy to learn Western poems",
    "description": "hello, welcome to our org",
    "logo": "https://helloworld.com/logo2.png",
    "company": "WebCompe"
}
```

### 返回
```json
{
    "id": 33,
    "name": "西方诗歌鉴赏",
    "slogan": "It's easy to learn Western poems",
    "description": "hello, welcome to our org",
    "logo": "https://helloworld.com/logo2.png",
    "company": "WebCompe"
}
```

## 更新机构成员角色信息
```
PUT /api/organization/:id/members
```
- :id  是创建机构的时候返回的 `id`

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`user_id`|`string`|是|需要更新的用户的 UUID|
|`role`|`string`|否|更新的权限，支持：teacher(不能进入机构后台，没有机构操作权限), student(不能进入机构后台，没有机构操作权限), maitainer(可以进入机构后台，有管理权限), owner(可以进入机构后台，有管理权限)，不传就不更新|

#### 请求示例
```json
PUT /api/organization/33/member
Content-Type: application/json
Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

{
    "user_id": "uuid",
    "role": "teacher"
}
```
### 返回
```
HTTP STATUS 200
```

### 错误
- 400 参数错误
- 500 内部错误
- 404 用户或者机构不存在

## 创建课程
```
POST /api/organization/:id/courses
```
- :id 机构ID

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`title`|`string`|是|课程的名称|
|`poster`|`string`|否|课程封面|
|`max_podium_user`|`int`|否|教室里可以同时进行连麦音视频互动的人数|
|`clarity`|`string`|是|清晰度。可选值 `Normal`: 标清 480P, `SD`: 高清 540P, `HD`: 超清 720P, `FHD`: 1080P|

#### 请求示例
```json
POST /api/organization/12/courses
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx

{
    "clarity": "FHD",
    "description": "没有东西",
    "duration": 2700,
    "max_podium_user": 6,
    "poster": "http://niuclass.qnsdk.com/FuxvQLL9",
    "title": "王维诗词鉴赏"
}
```

### 返回
```json
{
    "id": 9, // 课程ID
    "organization_id": 12,
    "creator_id": 5,
    "title": "王维诗词鉴赏",
    "poster": "http://niuclass.qnsdk.com/FuxvQLL9",
    "poster_url": "http://niuclass.qnsdk.com/FuxvQLL9",
    "description": "没有东西",
    "start": null, // 课程开始时间
    "end": null, // 课程结束时间
    "duration": 0,
    "period": 0,
    "white_id": "",
    "max_podium_user": 6,
    "clarity": "FHD",
    "created_at": 1551237497,
    "updated_at": 1551237497,
    "members": null,
    "times": null,
    "latest_class_time": null, // 下一堂课开课时间
    "finished_classes": 0 // 已经上完的课节数
}
```

## 更新课程信息
```
PUT /api/course/:id
```
- :id 课程ID, [创建课程](#%E5%88%9B%E5%BB%BA%E8%AF%BE%E7%A8%8B)的时候返回的 `id`

### 参数
如果不传，那么就不更新
|名称|类型|是否必须|描述|
|----|----|----|----|
|`title`|`string`|否|课程的名称|
|`poster`|`string`|否|课程封面|
|`max_podium_user`|`int`|否|教室里可以同时进行连麦音视频互动的人数|
|`clarity`|`string`|否|清晰度。可选值 `Normal`: 标清 480P, `SD`: 高清 540P, `HD`: 超清 720P, `FHD`: 1080P|

#### 请求示例
```json
PUT /api/course/12
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx

{
    "clarity": "HD",
    "description": "王维诗歌鉴赏",
    "duration": 2700,
    "max_podium_user": 6,
    "poster": "http://niuclass.qnsdk.com/FuxvQLL9",
    "title": "王维诗词鉴赏"
}
```

### 返回
```
HTTP STATUS 200
```

## 设置课程时间安排
```
PUT /api/course/:id/times
```
- :id [创建课程](#%E5%88%9B%E5%BB%BA%E8%AF%BE%E7%A8%8B)返回的 `id`

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`duration`|`int`|是|单堂课的时长|
|`period`|`int`|否|课程的周期，课时数|
|`times`| `[]struct`|是|参数是一个结构体数组，课程时间的具体安排, 参见|

#### times 结构体
|名称|类型|是否必须|描述|
|----|----|----|----|
|`start`|`timestamp`|是|课程开始日期，例如： 2019-02-22|
|`class_start`|`string`|是|课程开始的时间，例如：10:22|
|`repeat`|`string`|是|重复模式。可选项：`daily`: 每天重复，`weekly`: 每周重复，`none`: 不重复(单次课程)|
|`point`|`[]int`|否|当且仅当 `repeat == weekly` 的时候需要填，可选值：`1`: 礼拜一, `2`: 礼拜二, `3`: 礼拜三,`4`: 礼拜四, `5`: 礼拜五 ,`6`: 礼拜六, `7`: 礼拜天

#### 请求示例
```json
PUT /api/course/12/times
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx

当 repeat == weekly 时:
{
    "duration": 2700,
    "times": [{
        "start": 1551283200,
        "class_start": "11:20",
        "repeat": "weekly",
        "points": [3, 4, 5]
    }],
    "period": 22
}

当 repeat != weekly 时:

{
    "duration": 2700,
    "times": [{
        "start": 1551283200,
        "class_start": "11:20",
        "repeat": "none"
    }]
}

当有多个时间安排的时候：
{
    "duration": 2700,
    "times": [{
        "start": 1551283200,
        "class_start": "11:20",
        "repeat": "weekly",
        "points": [3, 4, 5]
    },
    {
        "start": 1551283200,
        "class_start": "14:20",
        "repeat": "none"
    }],
    "period": 22
}
```

### 返回
```
HTTP STATUS 200
```

## 设置课程成员
```
PUT /api/course/:id/members/:member_id
```
- :id [创建课程](#%E5%88%9B%E5%BB%BA%E8%AF%BE%E7%A8%8B)时返回的 `id`
- :member_id  [创建机构用户](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)时返回的 `member_id`

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`role`|`string`|是|这次课程的角色。可选值：`student`: 学生，`teacher`: 老师|

#### 请求示例
```json
PUT /api/course/12/members/22
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx

{
    "role": "teacher"
}
```

### 返回
```
HTTP STATUS 200
```

## 移除课程成员
```
DELETE /api/course/:id/members/:member_id
```
- :id [创建课程](#%E5%88%9B%E5%BB%BA%E8%AF%BE%E7%A8%8B)时返回的 `id`
- :member_id [创建机构用户](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)时返回的 `member_id`

### 参数
没有参数

#### 请求示例
```
DELETE /api/course/12/members/22
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx
```

### 返回
```
HTTP STATUS 204
```

## 课程信息
```
GET /api/course/:id
```
- :id  [创建机构用户](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)时返回的 `id`

### 参数
没有参数

#### 请求示例
```
GET /api/course/12
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx
```

### 返回
```json
{
    "id": 9,
    "organization_id": 2,
    "creator_id": 5,
    "title": "王维诗词鉴赏",
    "poster": "FuxvQLLJ3je85bQRA",
    "poster_url": "http://niuclass.qnsdk.com/FuxvQLLJ3je85",
    "description": "没有东西",
    "start": 1551283200,
    "end": 1564113900,
    "duration": 2700,
    "period": 22,
    "max_podium_user": 6,
    "clarity": "FHD",
    "created_at": null,
    "updated_at": 1551248515,
    "times": [{
        "id": 83,
        "course_id": 9,
        "start": 1551283200,
        "class_start": "11:20",
        "class_end": "12:05",
        "repeat": "weekly",
        "points": [3, 4, 5]
    }],
    "latest_class_time": 1551324000,
    "total_classes": 65,
    "finished_classes": 0,
    "state": "notstart"
}
```

## 删除课程
```
DELETE /api/course/:id
```
- :id [创建课程](#%E5%88%9B%E5%BB%BA%E8%AF%BE%E7%A8%8B)时返回的 `id`

### 参数
没有参数

#### 请求示例
```
DELETE /api/course/12
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx
```

### 返回 
```
HTTP STATUS 204
```

## 创建机构用户
```
POST /api/organization/:id/members
```
- :id 机构ID，在[niuclass](https://niuclass.qiniu.com)页面上可以查到

### 参数
|名称|类型|是否必须|描述|
|----|----|----|----|
|`role`|`string`|是|用户在机构里面的角色。可选项：`owner`: 机构拥有者，`maintainer`: 机构管理员，`teacher`: 老师，`student`: 学生|
|`mobile`|`string`|是|手机号，用户登录 niuclass 需要用来接收验证码|
|`name`|`string`|是|姓名|
|`title`|`string`|否|用户在机构的职称或者头衔|
|`bio`|`string`|否|用户描述|
|`avatar`|`string`|否|用户头像|
|`email`|`string`|否|用户邮箱|

#### 请求示例
```json
POST /api/organization/3/members
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx

{
    "role": "teacher",
    "mobile": "12992331122",
    "name": "张三",
    "title": "张老师",
    "bio": "张老师教语文的",
    "avatar": "https://hello.cowel/avatar.png",
    "email": "hwwww@qiniu.com"
}
```

### 返回
```json
{
    "user_id": 33,
    "member_id": 12,
    "name": "张三",
    "title": "张老师",
    "role": "teacher"
}
```

## 通过 MemberID 修改机构用户信息
```
PUT /api/organization/:id/members/:member_id
```
- :id 机构ID
- :member_id  [创建机构用户](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)时候返回的 `member_id`

### 参数
如果不传，那么就不修改
|名称|类型|是否必须|描述|
|----|----|----|----|
|`role`|`string`|否|机构用户的角色|
|`name`|`string`|否|用户的姓名|
|`title`|`string`|否|用户的职称或者头衔|
|`bio`|`string`|否|用户的描述|

#### 请求示例
```json
PUT /api/organization/3/members/12
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx

{
    "role": "student",
    "name": "李三",
    "title": "李同学",
    "bio": "李同学喜欢睡觉"
}
```

## 移除机构用户
```
DELETE /api/organization/:id/members/:member_id
```
- :id 机构ID
- :member_id  [创建机构用户](#%E5%88%9B%E5%BB%BA%E6%9C%BA%E6%9E%84%E7%94%A8%E6%88%B7)时候返回的 `member_id`

### 参数
没有参数

#### 请求示例
```
DELETE /api/organization/3/members/12
Content-Type: application/json
Authorization: Bearer xxxxxxxxxx
```