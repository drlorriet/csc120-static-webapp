.. parsonsprob:: unqiue_problem_id_here_lorrie
   :maxdist:
   :order:
   :language:
   :noindent:
   :adaptive:
   :numbered: left

   Instructions for the user.  These can include a textual description of how to solve the problem.  You must leave a blank line before this.
   -----
   def findmax(alist):
   =====
      if len(alist) == 0:
         return None
   =====
      curmax = alist[0]
      for item in alist:
   =====
         if item &gt; curmax:
   =====
            curmax = item
   =====
      return curmax
