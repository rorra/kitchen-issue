source "https://eligible.pe.jfrog.io/artifactory/api/gems/gems-remote/"

gem "rake"
gem "chef", "12.19.36"
gem "berkshelf"
gem "knife-acl"
gem "knife-zero"
gem 'knife-analytics'

gem 'savon'

# Token generator
gem "mkpasswd"
gem "base32"
gem 'htauth'

# AWS libraries
gem "net-ssh", "~> 4.0"
# AWS SDK Resources
gem "aws-sdk-cloudwatch", "~> 1"
gem "aws-sdk-ec2", "~> 1"
gem "aws-sdk-elasticache", "~> 1"
gem "aws-sdk-elasticloadbalancing", "~> 1"
gem "aws-sdk-iam", "~> 1"
gem "aws-sdk-s3", "~> 1"

gem "net-ping"
gem "rest-client"
gem 'knife-bastion'

gem "jmespath"

gem "json", "~> 2.3.1"

gem "faye-websocket", "~> 0.11.1"

gem "nokogiri", "~> 1.13.3"

gem "rack", "~> 2.2.4"

group :test do
  gem "test-kitchen", "~> 3.5.0"
  gem "kitchen-vagrant"
  gem "kitchen-docker"
  gem "rubocop", "~> 1.23.0"
  gem "foodcritic"
  gem "json-schema-rspec"
  gem "rspec"

  # gem "inspec", "~> 1.49.0" # Old version due to berkshelf old version, due to chef old version.
  # Impossible to install due to 1.49.0
end
