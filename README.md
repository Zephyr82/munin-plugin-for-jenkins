# What are these patch files intended for

These patch files are patching some jenkins related plugins from the offical munin-monitoring repo at github for use with FreeBSD 11. 
They change the directories to the standard installation directories for jenkins under FreeBSD and change some code that counts the number of jenkins jobs

# where are the original files

The original files are located at [the Github repo of munin-monitoring](https://github.com/munin-monitoring/munin/ "Link to the munin-monitoring Github repo")

Following files are being patched:

* [`jenkins_builds_results_summary`](https://github.com/munin-monitoring/munin/blob/master/plugins/node.d/jenkins_builds_results)
* [`jenkins_builds_results`](https://github.com/munin-monitoring/munin/blob/master/plugins/node.d/jenkins_builds_results)
* [`jenkins_builds`](https://github.com/munin-monitoring/munin/blob/master/plugins/node.d/jenkins_builds)
* [`jenkins_jobs`](https://github.com/munin-monitoring/munin/blob/master/plugins/node.d/jenkins_jobs)
