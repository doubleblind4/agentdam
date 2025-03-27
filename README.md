This repository contains dataset used in our **AgentDAM** benchmark.

Dataset is partitioned into 3 environments: gitlab, reddit, shopping. Each file contains a collection of tasks in webarena format: https://github.com/web-arena-x/webarena. The field 'intent' contains combined user_instruction + user_data fed into the LLM Agent.

system_prompt_privacy.json include system_prompt with CoT demonstrations used as a mitigation against privacy leakages.
