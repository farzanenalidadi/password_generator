# PasswordGenerator

**PasswordGenerator** is an Elixir module that generates random passwords based on various parameters. The module's main function is `generate(options)`, which takes an options map. You can configure the password's length and specify whether it should include numbers, uppercase letters, and symbols.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Supported Options](#supported-options)

## Installation

To use PasswordGenerator in your Elixir project, follow these steps:

1. Add the `PasswordGenerator` module to your Elixir project.

2. Call the `generate/1` function, passing the options map to create random passwords.

## Usage

To generate random passwords using **PasswordGenerator**, follow these steps:

1. **Generate Password**: Call the `generate/1` function with an options map to create a random password. The options map should include the following parameters:

    - `length`: The desired length of the password (as an integer).
    - `numbers`: Set to `"true"` or `"false"` to include or exclude numbers in the password.
    - `uppercase`: Set to `"true"` or `"false"` to include or exclude uppercase letters.
    - `symbols`: Set to `"true"` or `"false"` to include or exclude symbols.

   Here's an example options map:

   ```elixir
   options = %{
     "length" => "12",
     "numbers" => "true",
     "uppercase" => "false",
     "symbols" => "true"
   }

   ````

## Supported Options
The PasswordGenerator module supports the following options:

length: An integer specifying the desired password length.
numbers: Set to "true" to include numbers in the password, or "false" to exclude them.
uppercase: Set to "true" to include uppercase letters in the password, or "false" to exclude them.
symbols: Set to "true" to include symbols in the password, or "false" to exclude them.
You can configure these options to create passwords tailored to your requirements.

