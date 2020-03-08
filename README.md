
# 配置

## 安装依赖
```
yarn install
```

# 本地开发

## 启动前端

```
// 端口号是 7777
yarn run dev-js
```

## 启动后端

```
yarn run dev
```

# 部署

```
yarn run build-js
yarn run start
```

访问：http://127.0.0.1:7666/

在 Header 中追加以下字段

Authorization：ttttt899dfgd6fd65689f5g65f6g5f6gh
X-Access-Token：V1.0|pVgZ/f7G3XEaUH2pV6Q8uf6zXt18lSer8aIHYBlEVSmX5+nvHjmUm1MS2xtxkoycNQeNsIRkCrmyVuavWFqKimjQWI5O6MU9KFX1yKUs0siDsntXK/oyTiirh6DyxLUG

# 首页

## 最新课程
http://study.scho.com/front/basicCourse/getCourseLs.action?userId=1081449&pageNum=1&pageSize=6&orgId=3593&personGrpId=-1

# 精华推荐更多
http://study.scho.com/front/newTopical/getMoreSuggestTopicalLs?pageNum=1&pageSize=10

## 详情
http://study.scho.com/front/newTopical/getTopicCourseLs.action?topicalId=44274

## 课程详情
http://study.scho.com/front/basicCourse/getCourseDetail.action?userId=1081449&courseId=1920082&orgId=3593

# 最新课程更多

## 全部
http://study.scho.com/front/newBasicCourse/getColumnCourseLs.action?userId=1081449&pageNum=1&pageSize=10&orgId=3593&columnId=-1

## 类别
http://study.scho.com/front/newBasicCourse/getColumnLs.action?reqParam=

## 根据类别列表
http://study.scho.com/front/newBasicCourse/getColumnCourseLs.action?userId=1081449&pageNum=1&pageSize=10&orgId=3593&columnId=8

## 课程详情
http://study.scho.com/front/basicCourse/getCourseDetail.action?userId=1081449&courseId=14399053&orgId=3593

# 好课棒

## 评论榜
http://study.scho.com/front/search/searchMorestCommentNum?userId=1081449&pageNum=1&pageSize=10&orgId=3593

## 收藏榜
http://study.scho.com/front/search/searchMorestFavoriteNum?userId=1081449&pageNum=1&pageSize=10&orgId=3593

## 点赞榜
http://study.scho.com/front/search/searchMorestAppraise?userId=1081449&pageNum=1&pageSize=10&orgId=3593

# 主题
http://study.scho.com/front/newTopical/getSeriesLsWithTopical?pageNum=1&seriesParentId=10&pageSize=5

## 主题详情
http://study.scho.com/front/newTopical/getTopicCourseLs.action?topicalId=44445

# 栏目

## 轮播图
http://study.scho.com/front/newTopical/getSuggestTopicalLs?topicalColumnType=2

## 列表
http://study.scho.com/front/newTopical/getNewestColumns?pageNum=1&pageSize=10

## 栏目详情
http://study.scho.com/front/newTopical/getTopicCourseLs.action?topicalId=53819

# 闯关

## 列表
http://study.scho.com/front//game/6912/getGameDetail?userId=1081449

## 关卡详情
http://study.scho.com/front/game/getQuestFirstedPageInfoNew?userId=1081449&questId=355604&orgId=3593&gameId=6912

## 开始闯关
POST 
{
	"orgId": "3593",
	"taskFlag": "N",
	"questId": "355604",
	"userId": "1081449",
	"gameId": "6912"
}
http://study.scho.com/front/game/getQuestFirstedPageInfoNew?userId=1081449&questId=355604&orgId=3593&gameId=6912

{
	"orgId": "3593",
	"questInstId": "3997304",
	"contentType": "1",
	"contentId": "23829",
	"userId": "1081449",
	"questContentId": "1325531"
}
http://study.scho.com/front/game/getQuestContent

## 提交反馈
{
	"examQuestionParams": [{
		"userAnswer": [3811],
		"probResult": "",
		"optionResults": ["3811"],
		"optionIds": [3811],
		"examResultId": 4215593,
		"probId": 1048,
		"groupId": 0,
		"questionTypeId": 1,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3815, 3814, 3816],
		"probResult": "",
		"optionResults": ["3815", "3814", "3816"],
		"optionIds": [3815, 3814, 3816],
		"examResultId": 4215593,
		"probId": 1049,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3819, 3818, 3817, 3820],
		"probResult": "",
		"optionResults": ["3819", "3818", "3817", "3820"],
		"optionIds": [3819, 3818, 3817, 3820],
		"examResultId": 4215593,
		"probId": 1050,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3823, 3822, 3821],
		"probResult": "",
		"optionResults": ["3823", "3822", "3821"],
		"optionIds": [3823, 3822, 3821],
		"examResultId": 4215593,
		"probId": 1051,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3828, 3825],
		"probResult": "",
		"optionResults": ["3828", "3825"],
		"optionIds": [3828, 3825],
		"examResultId": 4215593,
		"probId": 1052,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3831, 3832],
		"probResult": "",
		"optionResults": ["3831", "3832"],
		"optionIds": [3831, 3832],
		"examResultId": 4215593,
		"probId": 1053,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3836],
		"probResult": "",
		"optionResults": ["3836"],
		"optionIds": [3836],
		"examResultId": 4215593,
		"probId": 1054,
		"groupId": 0,
		"questionTypeId": 1,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3838, 3839, 3840, 3837],
		"probResult": "",
		"optionResults": ["3838", "3839", "3840", "3837"],
		"optionIds": [3838, 3839, 3840, 3837],
		"examResultId": 4215593,
		"probId": 1055,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3841],
		"probResult": "",
		"optionResults": ["3841"],
		"optionIds": [3841],
		"examResultId": 4215593,
		"probId": 1056,
		"groupId": 0,
		"questionTypeId": 1,
		"usedTime": 1,
		"id": 0
	}, {
		"userAnswer": [3848, 3845],
		"probResult": "",
		"optionResults": ["3848", "3845"],
		"optionIds": [3848, 3845],
		"examResultId": 4215593,
		"probId": 1057,
		"groupId": 0,
		"questionTypeId": 2,
		"usedTime": 1,
		"id": 0
	}]
}
http://study.scho.com/front/exam/submitExamWithQuestions?examResultId=4215593&operType=1