% bundle exec nanoc
Loading site… done
Compiling site…

Captain! We’ve been hit!

ArgumentError: wrong number of arguments (given 2, expected 0..1)

Current item: /index.html (:default representation)

  0. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/temple-0.8.2/lib/temple/engine.rb:44:in `initialize'
  1. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-4.12.7/lib/nanoc/filters/haml.rb:25:in `new'
  2. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-4.12.7/lib/nanoc/filters/haml.rb:25:in `run'
  3. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/filter.rb:188:in `setup_and_run'
  4. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/executor.rb:67:in `layout'
  5. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/compilation_phases/recalculate.rb:34:in `block in run'
  6. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/action_sequence.rb:50:in `each'
  7. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/action_sequence.rb:50:in `each'
  8. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/compilation_phases/recalculate.rb:29:in `run'
  9. /Users/luc/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/gems/nanoc-core-4.12.7/lib/nanoc/core/compilation_phases/abstract.rb:23:in `call'
  ... 5 lines omitted (see crash.log for details)

A detailed crash log has been written to ./crash.log.

