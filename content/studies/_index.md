---
---
{{ $discipline = "UX/UI Design"}}
{{ $skill      = "Certified Usability Analyst - HFI\nDesign Thinking - Harvard"}}
{{ $details    = "Learned how to apply human factors - psychological and physiological principles - to product and system design, as well as design thinking innovation techniques."}}

{{ $discipline = "Software Engineering"}}
{{ $skill      = "B.S. ECE - Boston University"}}
{{ $details    = "Learned about Electrical and Software Engineering from first principles, supplemented by startup engineering experiences."}}

{{ $discipline = "Research"}}
{{ $skill      = "Certified Usability Analyst - HFI"}}
{{ $details    = "Learned data gathering methodologies and iterative usability testing techniques."}}


{{ $discipline = "Community Leader"}}
{{ $skill      = "Community Leadership Core - Jono Bacon"}}
{{ $details    = "Learning about how to start, sustain, and grow a world-class community from the Ubuntu community leader."}}


{{ $discipline = "Ethics"}}
{{ $skill      = "Young SDG Innovators Program - UN\nFoundations of Humane Tech - CHT"}}
{{ $details    = "Learned about how to effectively apply ethical design within for-profit companies, as well as exploring the solution space for game theoretic economies."}}

{{ $discipline = "Communication"}}
{{ $skill      = "Sharpen Your Communication - Stanford"}}
{{ $details    = "Learned behavioral science research behind effective communication practices to help refine my communication skills to be a compelling leader."}}

{{ $discipline = "Music"}}
{{ $skill      = "15+ Years Gigging"}}
{{ $details    = "Learned how to capture the attention of crowds, leading the human brain through cycles of tension and release."}}

{{ $discipline = "Product Management"}}
{{ $skill      = "Wicked Problem Solving Facilitator - PMI\nAssessing New Business Ideas - Harvard"}}
{{ $details    = "Learned techniques to solve complex problems by asking the right questions, visualizing information, and getting people to act."}}
{{partial "homepage-cards.html" (dict "context" . "discipline" $discipline "skill" $skill   "details" $details) }}