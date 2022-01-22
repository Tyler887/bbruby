
task TOP => [:default] do

  target = SITE_DIR + 'refact/'

  mkdir_p target, QUIET

  require 'refactoringHome'

  OutputCapturer.new.run {run_refactoring}

end

 
