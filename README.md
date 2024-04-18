# File Template
File Template을 통해 (Add File) 시 Custom Swift 파일을 만들 수 있다.
#### Custom Swift 파일

![init](https://github.com/Noyoungj/FileTemplate/assets/68863717/49d5ab92-06aa-4685-ad55-b416f6a699b1)

## 사용 방법
1. 'FileTemplates'와 'set_templates.sh'를 원하는 Xcode 프로젝트로 이동.
2. 터미널을 통하여 해당 Xcode 파일 경로로 이동.
3. './set_templates.sh' 명령어 입력
4. 프로젝트 실행 후 파일 만들기
5. 해당 파일이 'File Template'에서 보이지 않는다면, XCode를 완전히 닫고(Command + Q) 3번부터 다시 실행

### Use Case 항목
- Class Name: 만들 UseCase의 Name. 뒤에 UseCase 안 붙혀도 된다.(자동 입력)
- Repository Name: 내가 가져와서 쓸 Repository Name. 뒤에 Repository 안 붙혀도 된다.(자동 입력)
- Response Name: API 연동 시 받아올 Decodable Name. 뒤에 Response 안 붙여도 된다.(자동 입력)
- Check Box: Response 파일이 없을 경우, 'Response Name' 입력값으로 파일 생성
