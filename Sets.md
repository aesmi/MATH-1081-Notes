## Set Theory Basics
- A set is a collection of distinct objects, called elements.
- Sets are denoted by capital letters (e.g., A, B, C).
- The symbol ∈ is used to indicate that an element belongs to a set (e.g., x ∈ A means x is an element of set A).
- The symbol ∉ is used to indicate that an element does not belong to a set (e.g., x ∉ A means x is not an element of set A).
- The cardinality of a set A, denoted by |A|, is the number of elements in set A.
- The empty set, denoted by ∅ or {}, is a set with no elements.

## Set Operations
- Union: A ∪ B represents the set containing all elements that are in set A or set B, or both.
- Intersection: A ∩ B represents the set containing all elements that are common to both set A and set B.
- Difference: A - B (or A \ B) represents the set containing all elements that are in set A but not in set B.
- Complement: A' (or A̅) represents the set containing all elements in the universal set U that are not in set A.
- Cartesian Product: A × B represents the set of all ordered pairs (a, b) where a is in set A and b is in set B.

## Set Laws and Properties
1. Identity Laws:
   - A ∪ ∅ = A
   - A ∩ U = A
2. Domination Laws:
   - A ∪ U = U
   - A ∩ ∅ = ∅
3. Idempotent Laws:
   - A ∪ A = A
   - A ∩ A = A
4. Null Laws:
   - A ∪ A' = U
   - A ∩ A' = ∅
5. Complement Laws:
   - A ∪ A' = U
   - A ∩ A' = ∅
6. De Morgan's Laws:
   - (A ∪ B)' = A' ∩ B'
   - (A ∩ B)' = A' ∪ B'
7. Distributive Laws:
   - A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)
   - A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)

## Cardinality
- The cardinality of a set A, denoted by |A|, is the number of elements in set A.
- For example, if A = {1, 2, 3}, then |A| = 3.

### Cardinality Formulas
1. Cardinality of a Finite Set:
   - If A is a finite set containing distinct elements, the cardinality of A is given by the formula: `|A| = n`, where n is the number of elements in set A.

2. Cardinality of the Power Set:
   - If A is a finite set, the power set of A (denoted by P(A)) is the set containing all possible subsets of A, including the empty set and A itself. The cardinality of the power set of A is given by the formula: `|P(A)| = 2^n`, where n is the number of elements in set A.

3. Cardinality of the Cartesian Product:
   - If A and B are finite sets, the cardinality of the Cartesian product A × B is given by the formula: `|A × B| = |A| * |B|`, where |A| represents the cardinality of set A and |B| represents the cardinality of set B.

4. Cardinality of the Union of Disjoint Sets:
   - If A and B are disjoint (non-overlapping) sets, meaning A ∩ B = ∅, then the cardinality of their union is given by the formula: `|A ∪ B| = |A| + |B|`.

5. Cardinality of the Union of Non-disjoint Sets:
   - If A and B are sets with some elements in common, then the cardinality of their union is given by the formula: `|A ∪ B| = |A| + |B| - |A ∩ B|`.

6. Cardinality of the Set Difference:
   - If A and B are sets, the cardinality of the set difference A - B (or A \ B) is given by the formula: `|A - B| = |A| - |A ∩ B|`.

These formulas provide a basis for calculating the cardinality of different types of sets and set operations.
