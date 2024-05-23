# test-security-git

Test project that adds / removes security issues in commits

| # | Name | Hash | security issues changes | files with issue changes | total issues |
|---|------|------|-------------------------|---------------------------|--------------|
| 0 | Initial commit | d98e27e62428fe53137e46e5478070be914fd011 | - | 0 | 
| 1 | no issue commit | f9346fc8ab5ebb72cb2a942f6dd513c38e14a28b | - | 0 |
| 2 | Add IAC issue | 7c3fd7db3383133bd238876383b9041ce6eb8e29 | +1 IAC (high) | iac/req_sw_terraform_aws_alb_https_only.tf | 1 |
| 3 | Add py app | adcdec709cc8aecbcfb340cd32bf9d6e8236c02b | +2 SCA (high)<br> pip:24.0, flask:1.1.2 | py_app/requirements.txt | 3 |
| 4 | no issue commit | f65fd83f2c228f26c1e599157fed432e16ffe5bb | - | - | 3 |
| 5 | Add npm app | - | +1 SCA (high)<br> json:9.0.6 | npm_app/index.js | 4 |