# Trimming using sickle homework


### variables declaration
WD='/Users/soufiane/Assembly'
RAWDT='/Users/soufiane/Assembly/rawdata'
TRIMDT='/Users/soufiane/Assembly/trimmed'
LOGDR='/Users/soufiane/Assembly/logs'

#command to run sickle
sickle pe -t sanger -n -q 30 -l 50 -g -f $RAWDT/SRR3111247_1.fastq -r $RAWDT/SRR3111247_2.fastq -o $TRIMDT/trim_1.fastq -p $TRIMDT/trim_2.fastq -s $TRIMDT/0.trim.fastq > $LOGDR/sickle.log
