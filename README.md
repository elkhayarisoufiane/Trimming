# Trimming using sickle homework


### variables declaration
WD='/Users/soufiane/Assembly'
RAWDT='/Users/soufiane/Assembly/rawdata'
TRIMDT='/Users/soufiane/Assembly/trimmed'
LOGDR='/Users/soufiane/Assembly/logs'

#command to run sickle
sickle pe -t sanger -n -q 30 -l 50 -g -f $RAWDT/SRR3111247_1.fastq -r $RAWDT/SRR3111247_2.fastq -o $TRIMDT/trim_1.fastq -p $TRIMDT/trim_2.fastq -s $TRIMDT/0.trim.fastq > $LOGDR/sickle.log



### Ourput file 

PE forward file: /Users/soufiane/Assembly/rawdata/SRR3111247_1.fastq
PE reverse file: /Users/soufiane/Assembly/rawdata/SRR3111247_2.fastq

Total input FastQ records: 5724570 (2862285 pairs)

FastQ paired records kept: 1062546 (531273 pairs)
FastQ single records kept: 1121890 (from PE1: 528250, from PE2: 593640)
FastQ paired records discarded: 2418244 (1209122 pairs)
FastQ single records discarded: 1121890 (from PE1: 593640, from PE2: 528250)
