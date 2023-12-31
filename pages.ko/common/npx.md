# npx

> `npm` 패키지에서 바이너리 실행.
> 더 많은 정보: <https://github.com/npm/npx>.

- 로컬 또는 원격 `npm` 패키지에서 명령을 실행:

`npx {{명령어}} {{인자1 인자2 ...}}`

- 동일한 이름의 명령어가 여러 개 존재하는 경우, 패키지를 명시적으로 지정:

`npx --package {{패키지}} {{명령어}}`

- 현재 경로나 `node_modules/.bin`에 명령이 있는 경우 명령을 실행:

`npx --no-install {{명령어}} {{인자1 인자2 ...}}`

- `npx` 자체의 출력을 억제하는 특정 명령을 실행:

`npx --quiet {{명령어}} {{인자1 인자2 ...}}`

- 도움말 표시:

`npx --help`
