How to Use

1.  Open new tab, log in to https://scantist.io/login and login using Github (Auto).
2.  Open new tab, log in to https://travis-ci.org and login using Github (Auto).
3.  In the related maven repository, copy the dependency text under the Maven tab.
4.  In the pom.xml file, replace/add dependencies under the "Add dependencies here" label
5.  In Travis Cl, click on "Build history" tab to see all pending compilation jobs.
6.  Click on the pending compilation job. (Yellow label)

      - Recommended to run one job at a time.
      - If build does not show up after 2 minutes, click on More options->Trigger build
      - Normal for it to take around 3 minutes to start.
  
7.  Wait for compilation to complete. (Green Highlight)
8.  Switch to scantist tool tab and wait for a pop-up to appear at the top.
9.  Click on popup to be redirected to scan page.
10. Find related CVE (using browser's CTRL-F).
