Name: Terry Nii Odartey-Lamptey
Index Number: 5251570132
MoMo Number: 0555225459


actor Calculator {
  public func add(x: Nat64, y: Nat64): async Nat64 {
    return x + y;
  };

  public func sub(x: Nat64, y: Nat64): async Nat64 {
    return x - y;
  };

  public func mul(x: Nat64, y: Nat64): async Nat64 {
    return x * y;
  };

  public func div(x: Nat64, y: Nat64): async ?Nat64 {
    if (y == 0) {
      return null;
    };
    return ?(x / y);
  };
}
