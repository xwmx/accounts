```
                                                       **
                                                      /**
  ******    *****   *****   ******  **   ** *******  ******  ******
 //////**  **///** **///** **////**/**  /**//**///**///**/  **////
  ******* /**  // /**  // /**   /**/**  /** /**  /**  /**  //*****
 **////** /**   **/**   **/**   /**/**  /** /**  /**  /**   /////**
//********//***** //***** //****** //****** ***  /**  //**  ******
 ////////  /////   /////   //////   ////// ///   //    //  //////
```

# accounts

`accounts` is a command line / terminal tool for common macOS user account
operations, like fast user switching, listing users, and displaying the login
window.

## Installation

### Homebrew

To install with [Homebrew](http://brew.sh/):

```bash
brew install xwmx/taps/accounts
```

### bpkg

To install with [bpkg](http://www.bpkg.io/):

```bash
bpkg install xwmx/accounts
```

### Manual

To install manually, simply add the `accounts` script to your `$PATH`. If
you already have a `~/bin` directory, you can use the following command:

```bash
curl -L https://raw.github.com/xwmx/accounts/master/accounts \
  -o ~/bin/accounts && chmod +x ~/bin/accounts
```

## Usage

```
Usage:
  accounts list
  accounts login <username>
  accounts logout [--force]
  accounts window
  accounts -h | --help
  accounts --version

Subcommands:
  list    List login user accounts.
  login   Log in as the specified user, aka "Fast User Switching."
  logout  Log out the current user.
  window  Go to the login window without logging out.

Options:
  -h --help  Display this help information.
  --version  Display version information.
  --force    Suppress confirmation prompt.
```
