# gvpack

> 여러 그래프 레이아웃 (이미 레이아웃 정보가 있음을 결합)을 결합.
> 그래프비즈 필터: `acyclic`, `bcomps`, `comps`, `edgepaint`, `gvcolor`, `gvpack`, `mingle`, `nop`, `sccmap`, `tred`, & `unflatten`.
> 더 많은 정보: <https://graphviz.org/pdf/gvpack.1.pdf>.

- 이미 레이아웃 정보가 있는 여러 그래프 레이아웃을 결합:

`gvpack {{경로/대상/레이아웃1.gv}} {{경로/대상/레이아웃2.gv ...}} > {{경로/대상/출력파일.gv}}`

- 그래프 수준에서 여러 그래프 레이아웃을 결합하여, 그래프를 별도로 유지:

`gvpack -g {{경로/대상/레이아웃1.gv}} {{경로/대상/레이아웃2.gv ...}} > {{경로/대상/출력파일.gv}}`

- 클러스터를 무시하고, 노드 수준에서 여러 그래프 레이아웃을 결합:

`gvpack -n {{경로/대상/레이아웃1.gv}} {{경로/대상/레이아웃2.gv ...}} > {{경로/대상/출력파일.gv}}`

- 패킹 없이 여러 그래프 레이아웃 결합:

`gvpack -u {{경로/대상/레이아웃1.gv}} {{경로/대상/레이아웃2.gv ...}} > {{경로/대상/출력파일.gv}}`

- 도움말 표시:

`gvpack -?`
