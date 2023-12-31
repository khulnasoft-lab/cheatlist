# bzip2

> 블록 정렬 파일 압축기.
> 더 많은 정보: <https://manned.org/bzip2>.

- 파일 압축하기:

`bzip2 {{경로/대상/압축할_파일}}`

- 파일 압축해제하기:

`bzip2 -d {{경로/대상/압축된_파일.bz2}}`

- 파일을 표준 출력으로 압축해제:

`bzip2 -dc {{경로/대상/압축된_파일.bz2}}`

- 압축된 파일 내 각 파일의 무결성 테스트:

`bzip2 --test {{경로/대상/압축된_파일.bz2}}`

- 압축된 파일의 각 파일에 대한 압축률과 자세한 정보 표시:

`bzip2 --verbose {{경로/대상/압축된_파일.bz2}}`

- 기존 파일을 덮어쓰면서 파일 압축 해제:

`bzip2 --force {{경로/대상/압축된_파일.bz2}}`

- 도움말 표시:

`bzip2 -h`
