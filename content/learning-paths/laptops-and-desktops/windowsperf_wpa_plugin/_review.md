---
# ================================================================================
#       Edit
# ================================================================================

# Always 3 questions. Should try to test the reader's knowledge, and reinforce the key points you want them to remember.
    # question:         A one sentence question
    # answers:          The correct answers (from 2-4 answer options only). Should be surrounded by quotes.
    # correct_answer:   An integer indicating what answer is correct (index starts from 0)
    # explanation:      A short (1-3 sentence) explanation of why the correct answer is correct. Can add additional context if desired


review:
    - questions:
        question: >
            The WPA plugin connects WindowsPerf to the Windows Performance Analyzer. 
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            The Windows Performance Analyzer (WPA) plugin connects WindowsPerf to the Windows Performance Analyzer.

    - questions:
        question: >
            Which views can WPA display
        answers:
            - "Timeline"
            - "Telemetry"
            - "Function profile"
            - "Timeline and telemetry"
            - "All of the above"
        correct_answer: 3
        explanation: >
            WPA can display both the timeline and the telemetry views.

    - questions:
        question: >
            WindowsPerf can output data in JSON format with `--json` command line option.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            Some `wperf` commands such as `list`, `test` or `stat` can output data in JSON format.


# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---
