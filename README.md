```
/*
Copyright 2025 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

	https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
*/
```

# A generic repo template
A template for a generic repository with core files and directories to speed to project setup.


What are the files?

```
.
├── .aiexcludes					# used by Gemini Code Assist to exclude certain files or directories being indexed in GCA responses
├── .gitignore					# used by git to exlude files and directories under git management
├── .gemini
│   ├── config.yaml				# Gemini code assist code review agent configuration
│   ├── config-decriptions.yaml	# Gemini code assist code review agent configuration descriptions
│   ├── styleguide-example.md	# Gemini code assist code review agent detail on what to look at (example)
│   └── styleguide.md			# Gemini code assist code review agent detail on what to look at
└── .idx
    ├── dev.nix
    └── 

```
