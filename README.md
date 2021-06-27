# Graduation-Project-1
Bioinformatics를 활용한 COVID-19 염기서열 데이터 분석 및 응용

## complete_list_alignment.ipynb 사용법

1. covid.fasta 파일에 바이러스 염기서열을 모두 써준다.
2. number만큼 genbank_id를 입력하고 저장한다.
3. txt파일내에 있는 genbank_id에 해당하는 유전자의 염기서열을 covid.fasta 파일에  작성한다.
4. sequence alignment 후 aln 파일을 covid.aln이라는 이름으로 저장한다.

원하는 fasta 파일들의 multiple sequence alignment가 완료된 후 그 결과가 covid.aln파일에 저장되어 생성된다.

>다른 염기서열 데이터를 alignment하고 싶은 경우 ncbi에서 관리하는 염기서열 데이터의 네임 코드를 직접 입력하면 된다.
