task :default => [:test]

task :test do
  rspec spec --format RspecJunitFormatter --out test_results/TEST-rspec.xml
end
