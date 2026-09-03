# 원문 판본

이 프로젝트는 PerseusDL `canonical-greekLit`의 `perseus-grc2` TEI XML을 고정된 커밋과 SHA-256으로 보존합니다.

- 작품: 호메로스, 『일리아스』 (`urn:cts:greekLit:tlg0012.tlg001.perseus-grc2`)
- 판본: D. B. Monro · T. W. Allen 편, *Homeri Opera*, Editio Tertia, 제1–2권, Oxford, 1908–1920
- 저장소 커밋: `7b8a2c9636bd90c7684c00624a392d3058ae9d22`
- 파일 SHA-256: `15ab2da1201d6160db741e7806f12667f692d47e5884e216c3bd12b08efa4ce8`
- 라이선스: CC BY-SA 4.0

`python scripts/fetch_source.py`는 기록된 URL에서 파일을 받아 해시가 일치할 때만 교체합니다. `python scripts/build_data.py`는 24권, 15,687개 행, 1,054개 읽기 문단을 정적 JSON으로 만듭니다.

제9권 458–461행, 제11권 543행, 제14권 269행은 이 판본 XML의 행 번호에 존재하지 않습니다. 파서는 이를 숨기지 않고 `lineNumberGaps`에 기록합니다.
