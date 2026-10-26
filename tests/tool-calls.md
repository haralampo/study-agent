1. What terms do you know?

Run 1: list_terms {"tool": "list_terms", "args": {}}
Run 2: Same.

2. What does phishing mean?

Run 1: search_terms {"tool": "search_terms", "args": {"keyword": "phishing"}};
        get_term {"tool": "get_term", "args": {"name": "phishing"}}
Run 2: Same.
Answer: Both gave correct definition.

3. What do you know about encryption?

Run 1: search_terms {"tool": "search_terms", "args": {"keyword": "encryption"}};
        get_term {"tool": "get_term", "args": {"name": "symmetric encryption"}};
        get_term {"tool": "get_term", "args": {"name": "asymmetric encryption"}}
Run 2: Same.

4. How is symmetric encryption different from asymmetric?

Run 1: search_terms {"tool": "search_terms", "args": {"keyword": "symmetric encryption"}};
        search_terms {"tool": "search_terms", "args": {"keyword": "asymmetric encryption"}};
        get_term {"tool": "get_term", "args": {"name": "symmetric encryption"}};
        get_term {"tool": "get_term", "args": {"name": "asymmetric encryption"}}
Run 2: Same.

5. Quiz me on one term.

Run 1: list_terms {"tool": "list_terms", "args": {}}
Run 2: Same.

6. What is penetration testing?

Run 1: search_terms {"tool": "search_terms", "args": {"keyword": "penetration testing"}}
        search_terms {"tool": "search_terms", "args": {"keyword": "penetration}}
Run 2: Same.
Answer: Both asserted word was not in data set.