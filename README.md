# LIRKS
Linux shIm foR faKe oS

# Why
I very strongly dislike shallow OS compatibility checkers when I am on Arch Linux, which exists for some packages. So, this is just a shim with temporary activity for systemd and other system checks which could work if not for simple text checkers. But will work with LIRKS

# Goals
  - systemd periodic activity
  - system file emulation (simple)
  - package response for faking dependencies with objectively incorrect responses
  - simple docker like implementation with less frontend and lower resources
  - technically isolated applications, only active when needed
  - configurable through a simple config file (initial)
    = docker like config for more complex integrations
    = might eventually make it declarative

# 2nd Why
I am very bored
LIRKS is a funny pseudo-acronym
I hate containers and VM's as they are too intensive for this sort of implementation

# 2nd Goals
  - implement fast OS swapping
    = would be funny if I could make it a polyglot for OS
    = polyglot OS implementations lol
  - implement systemd passthrough
    = just needs one processing run to structure systemd in a way that would pass the same checks

# Documentation
  when I get to it

# Code
  - Rust with C shims for unsafe code.

# Supported OS
  - all of them so long as you can find out how to structure the backend system
  - will make some scaffholding to be able to extract it somehow eventually

# How
  - maybe not sure

# When
  - sometime soon in theaters near you
