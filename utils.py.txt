class Problem:
  def __init__(self):
    self.generate_samples()
    raise NotImplementedError('Nothing here')
    pass

  def generate_samples(self,size=10000,random_seed=1234):
    raise NotImplementedError('Nothing here')
    pass
  
  def find_solution(self,method=None):
    raise NotImplementedError('Nothing here')
    pass

  def visualize(self):
    raise NotImplementedError('Nothing here')
    pass


class Method:
  def __init__(self):
    pass

class GradientMethod(Method):
  def __init__(self):
    super(self).__init__()
    pass

class SGDMethod(GradientMethod):
  def __init__(self):
    super(self).__init__()
    pass


class ECSGDMethod(SGDMethod):
  def __init__(self):
    super(self).__init__()
    pass
