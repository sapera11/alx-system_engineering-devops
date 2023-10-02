REGULAR EXPRESSION


0.

#!/usr/bin/env ruby

puts ARGV[0].scan(/[S]chool/).join
1.
#!/usr/bin/env ruby
puts ARGV[0].scan(/hbttn/).join
puts ARGV[0].scan(/hbtttn/).join
puts ARGV[0].scan(/hbttttn/).join
puts ARGV[0].scan(/hbtttttn/).join
2.

#!/usr/bin/env ruby
puts ARGV[0].scan(/htn/).join
puts ARGV[0].scan(/hbtn/).join
3.

#!/usr/bin/env ruby
puts ARGV[0].scan(/hbt+n/).join
4.

#!/usr/bin/env ruby
puts ARGV[0].scan(/hbt*n/).join
5.

#!/usr/bin/env ruby
puts ARGV[0].scan(/(^h.n$)/).join
6.

#!/usr/bin/env ruby
puts ARGV[0].scan(/^\d{10,10}$/).join
7.

#!/usr/bin/env ruby
puts ARGV[0].scan(/[A-Z]/).join

