### RocksDB_YCSB_F2FS/Ext4
2021 한국 정보과학회 논문경진대회 학부생 부문 우수상 

[파일시스템에 따른 RocksDB 성능 분석.pdf](https://github.com/theran23/YCSB_RocksDB_filesystems/files/5745779/2020.KSC_._._full.pdf)

저자: 김세란 
지도교수님: S.W Lee / VLDB@SKKU

선행 연구: [Don’t stack your Log on my Log](https://github.com/theran23/vldb-linkbench/files/5499903/Logstacking.pdf)

참조: [실험 안내 document](https://github.com/theran23/YCSB_RocksDB_filesystems/files/5745785/default.docx) (@csoyee)

-----------------------
실험 설명

시스템: SSD - File system(F2FS/Ext4) - RocksDB (@YCSB)

사용한 tool: blktrace, iostat, smartctl, YCSB log, RocksDB log

알고자한 것: write pattern, (logical WAF), physical WAF, ops

---------------------------
실험 스크립트
1. [실험 전체 과정 스크립트](https://github.com/theran23/YCSB_RocksDB_filesystems/blob/main/scripts/README.md)
2. [CONFIGURATION FILES (workload, OPTIONSFILE.INI)](https://github.com/theran23/YCSB_RocksDB_filesystems/tree/main/conditions)
3. [RUN 스크립트](https://github.com/theran23/YCSB_RocksDB_filesystems/blob/main/scripts/run.sh)
---------------------------
결과 스크립트
(gnuplot)
1. [PHYSICAL WAF](https://github.com/theran23/YCSB_RocksDB_filesystems/blob/main/log_scripts/micron.sh)
2. [OPS](https://github.com/theran23/YCSB_RocksDB_filesystems/tree/main/log_scripts)
3. [BTRACE](https://github.com/theran23/YCSB_RocksDB_filesystems/tree/main/log_scripts)

--------------------------

실험 결과


[결과](https://github.com/theran23/YCSB_RocksDB_filesystems/tree/main/results)

--------------------------


참조 논문

[FlashKV](https://github.com/theran23/vldb-linkbench/files/5499897/FlashKV.pdf)
[Analyzing IO Amplification in Linux File Systems](https://github.com/theran23/vldb-linkbench/files/5499892/Analyzing.IO.Amplification.in.Linux.File.Systems.pdf)




