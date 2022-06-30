Detection logic is translated to generic SIGMA rule for flexibility of easy conversion to multiple log sources.

1. The majority of rules have been tested against SentinelOne EDR or Sysmon logs. These rules are considered stable. 
2. Any rules that have not been tested in some level of a simulated environment will be marked as experimental.
3. All rules should be tested in your environment before implementing due to potential unknown false positives that could occur.
4. Please post any major false positives that are found. Please do not add false positives of any detection that is heavily specific to your environment.