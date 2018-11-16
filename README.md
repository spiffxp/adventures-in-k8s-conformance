# Adventures in Conformance

This repo contains the source data used to generate charts for my talk
[Adventures in Conformance] for Kubecon China 2018.  Running the
`report.sh` script will unpack some api coverage databases that
were precomputed with an early version of [cncf/apisnoop], and
run a number of queries to reproduce the contents of `report.csv`.

If you'd like to get more raw data to use, you can head over to 
[testgrid] and [gubernator].

I used Google Sheets to generate charts from these numbers, which
I will leave as an exercise to the reader. The sunburst charts
were driven by the same data, and are currently available online
at https://apisnoop.cncf.ci/

It is my hope that this repo can soon be made redundant by the new
functionality that was demoed by the APISnoop team at their recent
KubeCon China 2018 talk [Discovering the Untold User Stories of Kubernetes
with Applied Anthropology].  Python > bash but it was the hammer
I had laying around at the time.

[Adventures in Conformance]: https://kccncchina2018english.sched.com/event/FuKh/adventures-in-conformance-aaron-crickenberger-google
[Disocvering the Untold User Stories of Kubernetes with Applied Anthropology]: https://kccncchina2018english.sched.com/event/FuKl/discovering-the-untold-user-stories-of-kubernetes-with-applied-anthropology-hippie-hacker-indigo-phillips-iicoop
[cncf/apisnoop]: https://github.com/cncf/apisnoop
[testgrid]: testgrid.k8s.io
[gubernator]: gubernator.k8s.io 
