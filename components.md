## Sample Component Model

```plantuml
[Requirement] <.. [Solution] : derive
[Solution] ..> [Camera] : integrate
[Camera] ..> [Optics] : integrate
[Camera] ..> [Interface] : connect
[Computer] ..> [Interface] : connect
[Solution] ..> [Computer] : integrate
[Computer] ..> [Software] : run
[Software] ..> [Workflow] : run
[Workflow] ..> [Preprocessing] : include
[Workflow] ..> [Classifier] : include
[Workflow] ..> [Analyzer] : include
[Workflow] ..> [Storage] : include
```
