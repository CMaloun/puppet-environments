#!/usr/bin/env ruby
#^syntax detection

forge "https://forgeapi.puppetlabs.com"

# A module from the Puppet Forge
  mod 'puppetlabs-stdlib'

# A module from git
  mod 'puppetlabs-ntp',
    :git => 'https://github.com/puppetlabs/puppetlabs-ntp.git'

# A module from a git branch/tag
  mod 'puppetlabs-apt',
    :git => 'https://github.com/puppetlabs/puppetlabs-apt.git',
    :ref => '1.4.x'

  mod 'puppet-testrepo',
    :git => 'https://github.com/CMaloun/puppet-testrepo',
    :branch => 'master'

mod 'apache',
    :git => 'https://github.com/CMaloun/puppet_apache',
    :branch => 'master'
