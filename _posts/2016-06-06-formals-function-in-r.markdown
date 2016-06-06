---
layout: post
title: "formals() function in R"
date: "2016-06-06 16:36:40 +1000"
---

{% include JB/setup %}

A simple way to access the list of parameters a function will accept [if it uses match.arg() which it should]

~~~~
R> formals(makeTxDbFromBiomart)
$biomart
[1] "ENSEMBL_MART_ENSEMBL"

$dataset
[1] "hsapiens_gene_ensembl"

$transcript_ids
NULL

$circ_seqs
DEFAULT_CIRC_SEQS

$filter
NULL

$id_prefix
[1] "ensembl_"

$host
[1] "www.ensembl.org"

$port
[1] 80

$taxonomyId
[1] NA

$miRBaseBuild
[1] NA

~~~~
