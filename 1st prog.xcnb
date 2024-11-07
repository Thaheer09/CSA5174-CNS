{
  "cells" : [
    {
      "content" : "## New Notebook  \n---  \nClick to edit this.",
      "creationTime" : 1730952485,
      "identifier" : "170DB61D-49CF-432F-962D-4222EC05A1D2",
      "isCollapsed" : false,
      "mutateTime" : 1730952487,
      "type" : "markdown"
    },
    {
      "content" : "\/\/ all\n#include <stdio.h>\n#include <stdlib.h>\n#include <string.h>\n#include <math.h>\n#include <time.h>\n#include <unistd.h>\n",
      "creationTime" : 1730952485,
      "identifier" : "60B04F75-A683-44E1-A53A-9E12ABCDD604",
      "isCollapsed" : false,
      "mutateTime" : 1730952485,
      "type" : "code"
    },
    {
      "content" : "The first line of the code cell **define the code's name** (if first line is comment), that can be include by others cell. Click ▶️ to run the code cell.",
      "creationTime" : 1730952485,
      "identifier" : "357B6BCD-D1E7-4907-BC37-ABA47BF78015",
      "isCollapsed" : false,
      "mutateTime" : 1730952485,
      "type" : "markdown"
    },
    {
      "content" : "#include <stdio.h>\n#include <ctype.h>\n\nvoid encrypt(char *plaintext, int key) {\n    for (int i = 0; plaintext[i] != '\\0'; i++) {\n        if (isalpha(plaintext[i])) {\n            char base = isupper(plaintext[i]) ? 'A' : 'a';\n            char encrypted_char = (plaintext[i] - base + key) % 26 + base;\n            printf(\"%c\", encrypted_char);\n        } else {\n            printf(\"%c\", plaintext[i]);\n        }\n    }\n}\n\nint main() {\n    char plaintext[100];\n    int key;\n\n    printf(\"Enter the plaintext: \");\n    fgets(plaintext, sizeof(plaintext), stdin);\n\n    printf(\"Enter the key (1-25): \");\n    scanf(\"%d\", &key);\n\n    if (key < 1 || key > 25) {\n        printf(\"Invalid key. Key must be in the range 1-25.\\n\");\n        return 1;\n    }\n\n    printf(\"Ciphertext: \");\n    encrypt(plaintext, key);\n    printf(\"\\n\");\n\n    return 0;\n}\n",
      "creationTime" : 1730952485,
      "identifier" : "0D69E2EE-2611-46F4-9A3B-76A050C6C231",
      "isCollapsed" : false,
      "mutateTime" : 1730952495,
      "result" : "Enter the plaintext: hello world\nEnter the key (1-25): 3\nCiphertext: khoor zruog\n",
      "runTime" : 1730952517,
      "type" : "code"
    }
  ],
  "codeResources" : "20d9b6f24f3a5e22c0da23ce39b7ecc833722809ba0229af8282976e7817ffbd",
  "creationTime" : 1730952485,
  "executeEngine" : "ccdinterp",
  "identifier" : "86509F82-8C7F-48C2-8750-81D48C5273FA",
  "latestOpenedTools" : "notebook",
  "latestOpenedToolsBuildId" : 551,
  "latestOpenedToolsVersion" : "3.7.0",
  "mutateTime" : 1730952517,
  "tools" : "notebook",
  "toolsBuildId" : 551,
  "toolsVersion" : "3.7.0",
  "version" : 4
}