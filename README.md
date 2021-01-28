# wide-use-crawl-bot
## concept
url과 tag 정보 혹은 xPath 처럼 다양한 정보를 가지고 주기적으로 크롤하고 알람을 주는 봇

## domain
- crawl
  - 아래 도메인(page, target, filter, notification)들을 포함.
  - crawl type
  - crawl term (cron expression 을 사용)
  - next crawl time
  - last crawl info
  - active status (boolean)
- login
  - login page
  - id
  - pw (암호화 적용)
  - auto login
- page
  - 크롤하려는 페이지와 태그까지만??
  - page url
  - target tag
- target
- filter (필터는 여러개가 존재할 수 있으며, 등록된 순서대로 필터링을 해야한다)
  - 태그로 부터 원하는 정보만 필터링 하기 위함
  - filter type
  - result type
  - order (unique)
- notification
  - 알림을 위한 정보
  - notification type
  - template
